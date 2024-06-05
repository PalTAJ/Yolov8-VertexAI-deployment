# Yolov8-VertexAI-deployment


This repo will include the code nessecary to deploy Yolov8 model on Google Cloud Vertex AI Endpoints (online prediction).

Deploying a YOLOv8 model on Google Cloud Platform (GCP) using Vertex AI involves several steps, from preparing your model and creating a Flask application, to containerizing your app, and finally deploying it for online predictions. Below is a high-level overview of the steps you need to follow:
1. Prepare Your YOLOv8 Model
2. Create a Flask Application
3. Containerize Your Flask Application
4. Upload the Model to Vertex AI Model Registry
5. Deploy the Model on Vertex AI for Online Predictions


Helping commands (avaiable in article):
To build the image run the following command on the terminal on workbench:
```
docker build -t gcr.io/{PROJECT ID}/{IMAGE NAME} .
```
after the build is done, we need to push the image to Container Registry using this command:
```
docker push gcr.io/{PROJECT ID}/{IMAGE NAME}
```
