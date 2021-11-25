# k8s-example-voting-app

```
kubectl create namespace example-voting-app
kubectl create -f redis-deployment.yaml --namespace example-voting-app
kubectl create -f redis-service.yaml --namespace example-voting-app
kubectl create -f db-deployment.yaml --namespace example-voting-app
kubectl create -f db-service.yaml --namespace example-voting-app
kubectl create -f vote-deployment.yaml --namespace example-voting-app
kubectl create -f vote-service.yaml --namespace example-voting-app
kubectl create -f result-deployment.yaml --namespace example-voting-app
kubectl create -f result-service.yaml --namespace example-voting-app
kubectl create -f worker-deployment.yaml --namespace example-voting-app
kubectl create -f voter-deployment.yaml --namespace example-voting-app
kubectl create -f observer-deployment.yaml --namespace example-voting-app

```
