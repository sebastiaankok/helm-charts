[![Lint and Test Charts](https://github.com/sebastiaankok/helm-charts/actions/workflows/ci.yaml/badge.svg)](https://github.com/sebastiaankok/helm-charts/actions/workflows/ci.yaml)
[![Release Charts](https://github.com/sebastiaankok/helm-charts/actions/workflows/release.yaml/badge.svg)](https://github.com/sebastiaankok/helm-charts/actions/workflows/release.yaml)


## Installation

### Add Helm repository

```shell
helm repo add sebastiaankok https://sebastiaankok.github.io/helm-charts
helm repo update
```

## Install wp-bedrock chart

Using config from a file:

```bash
helm install --generate-name sebastiaankok/wp-bedrock -f values.yaml
```
