# k8s-webApp Project

This is very basic Web Application project in which I deployed Application with Database in kubernetes cluster.


# Project Description:-

In this project I deploy mongoDB database and a Web application which is connect to the mongoDB database using external configuration data from configMap and Secret on Kubernetes cluster.

Project contains 4 Configuration files,
- **mongo-config.yaml**		file have mongoDB database endpoint.

- **mongo-secret.yaml**  (It contains username and password for mongoDB)

- **mongo.yaml**  (mongoDB Service and Deployment are grouped in one file. service is internally accessible)

- **webApp.yaml**  (Simple web application, it also has both deployment and service configuration grouped in one file. Service is externally accessible by using NodePort service type)

Source: **Nana Janashia**
