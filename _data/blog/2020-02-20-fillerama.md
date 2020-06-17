---
template: BlogPost
path: /fillerama
date: 2020-02-20T14:59:36.571Z
title: 'Kubernetes-101: Why are Containers so useful'
thumbnail: /assets/k8-icon.png
---
#k8 #kubernetes #docker #containers

## Deployments

### Understanding the evolution of deployments

![](k8-containers/FD50498D-7532-40C6-88B7-AEAEC029F394%205.png)
[source](https://kubernetes.io)

#### Traditional:
* Applications ran on physical servers. 
* No way to define resource boundaries for applications

#### Virtualized:
* Run multiple Virtual Machines (VMs) on a single physical server’s CPU. 
* Application isolation between VMs
* Security as a result of the isolation

#### Container: 
* Share the Operating System (OS) among the applications. 
* Lightweight. 
* Own filesystem, CPU, memory, process space, etc. 
* Decoupled from infrastructure, 
* Portable.

## Benefits Provided by Containers:
* Agile Delivery
* Continuous development, integration, and deployment.
* Observability
* Addresses Environment Drift.
* Portability
* Loosely coupled - not monolithic
* Ability to define resource boundaries - resource isolation, efficient utilization.


## Container Ecosystem Evolution

![](k8-containers/A74FCFD0-2451-4C87-AD10-3239C7E28D59%205.png)
[source](https://www.opcito.com/)


## Microservice Technology Timeline

![](k8-containers/5C428D20-1824-45D3-8C6C-68EEB75F88A3%205.png)
[source](https://www.researchgate.net/figure/A-microservice-technologies-timeline_fig1_324959590)



