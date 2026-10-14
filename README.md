<<<<<<< HEAD
# AZURE-CICD-Deployment-with-Github-Actions

## Authentication

Use the registry login command below and enter credentials when prompted. Do not store credentials in this file.


## Run from terminal:

docker build -t flasksimpleapp.azurecr.io/mltest:latest .

docker login flasksimpleapp.azurecr.io

docker push flasksimpleapp.azurecr.io/mltest:latest


## Deployment Steps:

1. Build the Docker image of the Source Code
2. Push the Docker image to Container Registry
3. Launch the Web App Server in Azure 
4. Pull the Docker image from the container registry to Web App server and run 
=======
# AzureDockerDeployment
WebApp Deployment
>>>>>>> 1d6a2827b45f04ac6b65a6b1630521d9dbfd59ca
