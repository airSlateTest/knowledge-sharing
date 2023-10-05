# Umbrella Chart, Nginx chart demo in micro infra

### Commands

```bash
helm lint

helm dependency build

helm package .

helm install --namespace knowlade-sharing-demo umbrella-demo-app ./umbrella-demo-app-1.0.tgz -f values.yaml

helm upgrade --namespace knowlade-sharing-demo --reuse-values --set global.image.tag="1.25.2" umbrella-demo-app ./umbrella-demo-app-1.0.tgz
```

### Useful links

[helm examples](https://github.com/pdffiller/helm-charts/blob/master/examples/README.md)

[helm building blocks Coliseum meeting](https://pdffiller.atlassian.net/wiki/spaces/DT/pages/3985309840/Helm+chart+k8s-app-v2+helm+building+blocks)

[helm building blocks Confluence](https://pdffiller.atlassian.net/wiki/spaces/IP/pages/3982753964/Helm+chart+building+blocks)