# Istio Example

This repo is an example k8s cluster with Istio installed. I followed [this](https://www.youtube.com/watch?v=voAyroDb6xk) tutorial from [TechWorld with Nana](https://www.youtube.com/c/TechWorldwithNana).

## Dependencies

- Istioctl
  - I used [brew](https://formulae.brew.sh/formula/istioctl) to install istioctl
- Docker
- Kubernetes

## Setup

- The first step is to run `istioctl install` on the cluster. This will...🥁 install istio on the cluster.
- That's it! Istio is now setup on the cluster, but now let's add a microservice for istio to talk to.