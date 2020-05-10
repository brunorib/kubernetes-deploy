# kubernetes-deploy
kubernetes based deployment of api-gateway, auth, workflow and worker.

# Get a kubernetes cluster
https://microk8s.io/#get-started

# Cluster deploy
clone this repository

use 
$kubectl apply -f .

on folders in order:
configmaps/
databases/
rabbitmq/
microservices/

To get the status of the cluster deployments, services... at any time:
kubectl get all

To scale the app, just change the number of replicas on any file *deployment.yml
