# 2. YAML in Kubernetes and kubectl apply

### Commands
```bash
helm create nginx-demo

kubectl apply -f manifests/namespace.yaml

kubectl get namespaces

kubectl apply -f manifests/deployment.yaml

kubectl get po -n knowlade-sharing-demo

kubectl port-forward -n knowlade-sharing-demo nginx-deployment-85996f8dbd-qxstg 8080:80
```
