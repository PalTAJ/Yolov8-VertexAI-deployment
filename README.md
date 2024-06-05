# Yolov8-VertexAI-deployment


This repo will include the code nessecary to deploy Yolov8 model on Google Cloud Vertex AI Endpoints (online prediction).

Article: Here


Helping commands (avaiable in article):
To build the image run the following command on the terminal on workbench:
```
docker build -t gcr.io/{PROJECT ID}/{IMAGE NAME} .
```
after the build is done, we need to push the image to Container Registry using this command:
```
docker push gcr.io/{PROJECT ID}/{IMAGE NAME}
```
