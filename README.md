### Project Details and architechures
This is realtime project with python rabbitmq where the final deployment destination is kubernetes. Minikube is the testing ground for dev environment , will be deployed on-premise k0s cluster with full observability and tracing . The main code is copied from here https://github.com/selikapro/microservices-python and I added the tracing and observability ,monitoring part to this project . Hope you will enjoy this.
There are 5 services named auth ,gateway ,rabbitmq,converter and notification service. For log analysis ELK is a nice tool to use , or you can use anything you love. For this project I configured ELK for log analysis and Jaeger for tracing .
