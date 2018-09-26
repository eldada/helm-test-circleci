# Helm Chart testing with CircleCI
This repository is an example for testing a [helm](https://www.helm.sh/) chart with [CircleCI](https://circleci.com)

The testing is made up of two stages:
1. Running a `helm lint` on the chart
2. Deploying chart to a running minikube Kubernetes cluster and validating http response code



## Thanks
This repository is using examples from
- https://github.com/gavinzhou/ci-minikube. Thanks [Gavin Zhou](https://github.com/gavinzhou)!
