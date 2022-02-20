# charts# kolikons Helm repository

Add kolikons repository to Helm repos:

```bash
helm repo add kolikons https://charts.kolikons.io
```

## Install label-watch

```bash
helm upgrade -i label-watch kolikons/label-watch \
--namespace kube-system
```
