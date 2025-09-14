# Task4 Roles and users in Kubernetes

1. Start minikube
```
minikube start
```

2. Create namespace
```
kubectl create namespace propdevelopment
```

3. Create users, roles, bindings
```
kubectl apply -f ./users.yaml
kubectl apply -f ./roles.yaml
kubectl apply -f ./role-bindings.yaml
```