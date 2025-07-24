# ML-Model-Deployment
There are various methods for deployment:

## Purpose of Model Deployment

In simple words:
           	- Model deployment makes your trained ML model useful in the real world — outside your Jupyter Notebook or local machine.

 ## Why do we deploy a model?

**1.Make predictions for real users**

	- You trained a model, but it’s useless if only you can run it on your laptop.

	- Deployment lets anyone (a user, app, website, or another system) send new data → get predictions back instantly.

**2.Put the model in production**

	- Deployment means putting your model into a live environment (e.g., a web server, cloud app, mobile app).

	- So real-time decisions can be made:

	- Spam detection on incoming emails

	- Credit card fraud alerts

	- Product recommendations

	- Medical diagnosis support

**3.Serve many requests automatically**

	- A deployed model can handle thousands of requests per minute if needed.

	- You don’t have to run your Python script manually for every prediction.

**4.Integrate with other systems**

	-   Businesses, apps, or websites need predictions programmatically.

Example: An e-commerce website calling your fraud model API for every transaction.

**5.Scale up easily**

	- Once deployed, you can scale to handle more users.

	- Use cloud services (AWS, GCP, Azure) to run multiple copies of your model API.

## How do you deploy a model?

Common way:

	- Save the trained model (pickle/joblib).

	- Wrap it with an API server (Flask, FastAPI, Django REST).

	- Deploy the API to the cloud or a server.

	- Now, users can send HTTP requests (JSON) → get predictions back.

## One-liner summary
Model deployment turns your ML code into a working product that people, apps, or businesses can actually use. 
