---
title: Overview, intial setup
---

## Prerequisites

* [Docker](https://docs.docker.com/desktop/)
* [Minikube](https://minikube.sigs.k8s.io/docs/start/) Version 1.28.0 (using Kubernetes 1.25.3)
* [git](https://git-scm.com/downloads)
* [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) Version 1.25.3
* [stern](https://github.com/stern/stern/releases) 


You may not know `stern`: it allows you to tail (follow) the logs of multiple pods on Kubernetes and multiple containers within the pod. It keeps displaying the logs when a pod is stopped and restarted. Each result is color coded for quicker debugging. 
