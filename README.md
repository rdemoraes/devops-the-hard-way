# Devops The Hard Way

This is just a hands-on guide for people looking for become a DevOps Engineer (I don't like the idea of using the DevOps as a role, but we lost this battle to the industry).

## Copyright

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

## Audience

The audience for this tutorial is someone looking for become a DevOps Engineer.

## What will be covered on this guide?

DevOps The Hard Way guides you through install most important tools used in the day-by-day of a DevOps Engineer, and also covering a lot of concepts about Agile Methodologies, the DevOps culture and automation (Yes, let's try to get some fun with it!).

### DevOps Culture

* [The Phoenix Project](https://github.com/keyvanakbary/learning-notes/blob/master/books/the-phoenix-project.md)
* [The DevOps Culture](https://github.com/devops-culture-project/devops-culture)

### Agile Methodology

* key concepts
* Frameworks
    * [scrum]()
    * [xp]()
    * [kanban]()

### Security Concepts

* Frameworks
    * [zero trust concept](https://about.gitlab.com/blog/2022/08/17/why-devops-and-zero-trust-go-together/?utm_campaign=blog&utm_source=twitter&utm_medium=social&utm_content=1660746252)

### Software Development

* Data Structures
    * [Arrays]()
    * [Stacks]()
    * [Queues]()
    * [Linked Lists]()
    * [Trees]()
    * [Graphs]()
    * [Tries]()
    * [Hash Tables]()

    Reference: [FreeCodeCamp](https://www.freecodecamp.org/news/the-top-data-structures-you-should-know-for-your-next-coding-interview-36af0831f5e3/#:~:text=Simply%20put%2C%20a%20data%20structure,for%20the%20problem%20at%20hand.)

* Logic Operators

* Programming Language
    * python
        * [pip package manager]()
    * javascript
        * 
        * package managers
            * [npm dependency package manager]()  # Install dependency packages sequentially
            * [yarn dependency package manager]() # Install dependency packages in parallel

* design patterns
    * [Domain-Driven Design]()

* Database
    * SQL
        * [postgresql]() # Used as the primary data store or data warehouse for many web, mobile, geospatial, and analytics applications.
    * NoSQL
        * [redis]()   # In-memory key-value data structure store
        * [mongodb]() # tool that can manage document-oriented information, store or retrieve information

### Infrastructure-as-Code

* key concepts
* tools
    * [terraform](https://github.com/hashicorp/terraform)

### Networking concepts

* [The OSI Model](https://github.com/vald-phoenix/the-osi-model)

### Cloud Services

* key concepts
    * [The NIST definition of cloud computing](https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-145.pdf)
* Cloud Providers
    * [AWS]()
    * [GCP]()

### Container runtimes

* [docker](https://github.com/docker/getting-started)
* [containerd](https://github.com/containerd/containerd)

### Kubernetes

* key concepts using a local cluster
    * [microk8s](https://github.com/canonical/microk8s)
    * [container runtime](https://kubernetes.io/docs/setup/production-environment/container-runtimes/#containerd)
* security & governance
    * [OPA Gatekeeper](https://github.com/open-policy-agent/gatekeeper)
        * [Rego Language - Used by the OPA](https://github.com/open-policy-agent/opa/blob/main/docs/content/policy-language.md)
    * [Popeye - A Kubernetes Cluster Sanitizer](https://github.com/derailed/popeye)
    * [kubeaudit](https://github.com/Shopify/kubeaudit)
    * [kube-no-trouble](https://github.com/doitintl/kube-no-trouble)
    * [kubesec](https://github.com/controlplaneio/kubesec)
    * [kube-bench](https://github.com/aquasecurity/kube-bench)
* deployment tools
    * [helm](https://github.com/helm/helm)
    * [kustomize](https://github.com/kubernetes-sigs/kustomize)
* monitoring & alerts
    * [prometheus stack]()
    * [prometheus adapter]()
    * [grafana]()

### GitOps Framework & Tools

* key concepts
* tools
    * [argocd](https://github.com/argoproj/argo-helm/tree/main/charts/argo-cd)
    * [fluxcd v2](https://github.com/fluxcd/flux2/tree/v0.32.0)

### CI CD & Tools

* key concepts
* CI CD tools
    * [gitlab-ci](https://docs.gitlab.com/charts/installation/deployment.html#deploy-using-helm)
* Tools
    * building container images
        * [docker's buildx plugin](https://github.com/docker/buildx)
        * [kaniko](https://github.com/GoogleContainerTools/kaniko)
        * [podman](https://github.com/containers/podman)
        * [buildah](https://github.com/containers/buildah)
    * Static code analysis for IaC:
        * [checkov](https://github.com/bridgecrewio/checkov)

## Tools used in this guide

* [microk8s](https://github.com/canonical/microk8s) v1.24.0
* [helm](https://github.com/helm/helm) v3.9.3
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