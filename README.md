# consul-k8s-base-demo
Quick start local Consul K8s environment 

## Prereqs

* Local K8s running
* Helm

## Install Brew
```bash
brew tap hashicorp/tap
brew install hashicorp/tap/consul-k8s
helm repo add hashicorp https://helm.releases.hashicorp.com
brew upgrade
brew upgrade --cask
```

## Setup Consul
```bash
consul-k8s install -f config.yaml
```

## Configure Consul
