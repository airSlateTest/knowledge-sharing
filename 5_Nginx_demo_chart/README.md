# 3. Helm Chart, Helm repository, Nginx chart demo

### Commands
```bash
helm lint

helm dependency build

helm template . --output-dir=rendered

helm package nginx-demo

helm install --namespace knowledge-sharing nginx-demo ./nginx-demo-0.1.0.tgz -f values.yaml
```

