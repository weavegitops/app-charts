# app-charts
A Git repostiory demo apps

Add your helm charts sources to the charts directory.


```
apiVersion: source.toolkit.fluxcd.io/v1beta1
kind: HelmRepository
metadata:
  name: weaveworks-charts
  namespace: flux-system
spec:
  interval: 1m
  url: https://weavegitops.github.io/app-charts/
```
