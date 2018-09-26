# Helm Chart testing with CircleCI
This repository is an example for testing a [helm](https://www.helm.sh/) chart with [CircleCI](https://circleci.com)

## CircleCI
See the CircleCI [config.yml](.circleci/config.yml) for the steps done to setup and test the helm chart

## CircleCI build status
[![CircleCI](https://circleci.com/gh/eldada/helm-test-circleci.svg?style=svg)](https://circleci.com/gh/eldada/helm-test-circleci)
[![CircleCI](https://circleci.com/gh/eldada/helm-test-circleci.svg?style=shield)](https://circleci.com/gh/eldada/helm-test-circleci)

## The tests
The testing is made up of two stages:
1. Running a `helm lint` on the chart
2. Deploying chart to a running minikube Kubernetes cluster and validating http response code


## Thanks
This repository is using examples from
- https://github.com/gavinzhou/ci-minikube. Thanks [Gavin Zhou](https://github.com/gavinzhou)!
