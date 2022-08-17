# Devops The Hard Way

This is just a guide for people looking for become a DevOps Engineer (I don't like the idea of using the DevOps as a role, but we lost this battle to the industry).

## Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Audience

The audience for this tutorial is someone looking for become a DevOps Engineer.

## What will be covered on this guide?

DevOps The Hard Way guides you through install most important tools used in the day-by-day of a DevOps Engineer, and also will cover a lot of concepts about Agile Methodologies, the DevOps culture and automation (Yes, let's try to get some fun with it!).

### Agile Methodology

...[in progress]...

### DevOps Culture

...[in progress]...

### Programming Language

* [python]()
* [javascript]()

### Basic-Networking

...[in progress]...

### GitOps Framework

...[in progress]...

### Cloud Providers

...[in progress]...

### Infrastructure-as-Code

...[in progress]...

## Tools used in this guide

* [microk8s](https://github.com/canonical/microk8s) v1.24.0
* [helm3](https://helm.sh/docs/intro/install/) v3
* [gitlab-ci](https://docs.gitlab.com/charts/installation/deployment.html#deploy-using-helm) v1.4.4
* [argocd](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd) v4.10.6
* [fluxcd v2](https://github.com/fluxcd/flux2/tree/v0.32.0) v0.32.0
* [kustomize](https://github.com/kubernetes-sigs/kustomize) v4.5.2
* [terraform](https://github.com/hashicorp/terraform) v1.2.7

## Labs

* [Prerequisites]()
* [Installing the microk8s. It is a local kubernetes cluster ]()
* [Installing the Client Tools]()
* [Provisioning the CA and Generating TLS Certificates]()
* [Installing the Gitlab CI]()
* [Installing ArgoCD]()
* [Installing the fluxcd v2]()
* [Deploy an application using the Gitlab CI (push-based method)]()
* [Deploy an application using the GitOps with ArgoCD (pull-based method)]()