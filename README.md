# MLflow Introductory Guide

This repository contains runnable notebooks that allow you to have a glimpse of the workflow of mlflow, the notebooks are designed in a way that is very concise, with each notebook having ~ 5 minutes read. For further reference, you may take a look at the references in mlflow_resources notebook and the official documentation.


### **1. MLflow Local Edition**
- Installation of mlflow
- Connecting mlflow to the environment 
- Example iris_model to demonstrate logging & metadata to be viewed on mlflow ui
- Model serving + calling the model with `curl` and through Python request library
- Building a docker image (more on 4. Docker Quick Guide)

### **2. MLflow_SQLite Local Database Edition**
- Connecting mlflow to database such as sqlite as backend store to store metadata
- Undestanding the structure of the database constructed by mlflow
- Demonstrating model serving + docker image with local database (similar to 1. MLflow Local Edition)

### **3. MLflow workflow with remote tracking server**
- Demonstrated workflow with remote tracking server (DagsHub) to simulate team collaboration environment
- Same iris_model example (1. MLflow Local Edition) is used to demonstrate model logging, serving, deployment, and docker building

### **4. Docker Quick Guide**
- Understanding what is docker
- Installation of docker
- Creating docker image
- Running docker container
- Using `curl` and request library to access the model from the container
- Pushing the docker image to docker hub
- Pulling a docker repository
- Copy docker image from one host to another without pushing/pulling

### **5. Tracking Server with Reverse Proxy (NGINX)**

### **6. Prophet_MLflow**
- Using prophet model as model to be logged to mlflow with example
- Logging with mlflow built in function + predicting with curl and through request library
- Constructing custom wrapper to cope with Prophet's custom input methodology
- Calling the custom wrapper through docker and predicting with curl and through request library

### **mlflow_features**
- Concept Guide of mlflow
- Setting/Connecting mlflow experiments
- How to log a run
- Model Registry and Versioning

### **mlflow_resources**
- Different useful references and resources demonstrated in the notebook
- Extended examples
- Common bugs and errors 
