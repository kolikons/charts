# kolikons Helm repository

Add kolikons repository to Helm repos:

```bash
helm repo add kolikons https://kolikons.github.io/charts/
```

## Install label-watch

```bash
helm upgrade -i label-watch kolikons/label-watch \
--namespace kube-system
```
