
# FastTrack for Azure - CaaS Developer Credentialing  
The credentialing process for FastTrack Engineers looking to pursue the CaaS developer credential 

The goal of the CaaS Developer Credentialing is to quickly verify and/or identify areas of growth to focus your development and learnings. The Service leads want to ensure there is a consistent credentialing experience that ensures the engineer can confidently deliver Container engagements.

## Credentialing Process
The credentialing process for CaaS Infrastructure will be partially performance based. This means the facilitator will ask questions to the engineer on how to accomplish a task and the engineer will actively work through the task either through the portal, CLI, or both. Due to the fact that this credentialing process is partially performance based, this means that the credentialing appointment will need both participants available to attend a screen share. 

<!-- ### Credentialing Session Requirements
When you feel that you are familiar and comfortable with the credentialing topics and curriculum, please feel free to contact the service lead to schedule your credentialing session. Please also make sure the following requirments have been met.

- Familiarize yourself with the credentialing curriculum topics
- Identify one of the service leads to conduct the credentialing session
- Ensure you have a running 3-node AKS cluster (RBAC enabled) available to work on during the session
- Ensure you have an Azure Container Registry that can access the AKS cluster
- Ensure you have the Azure Monitor Container Insights solution deployed to the AKS cluster
- Ensure you have an Azure Container Instance service deployed
- Ensure you have **1 hour** scheduled of uninterruptable time dedicated to the credentialing session -->
### Docker Credentialing Curriculum

#### Containerization Fundementals

#### Creating and running Images to debug locally

#### Dockerfile best practices
- Understand Dockerfile syntax
  - https://docs.docker.com/engine/reference/builder/
- Understand Dockerfile recommended practices
  - https://docs.docker.com/develop/develop-images/dockerfile_best-practices/
- Understand multi-stage build patterns
  - https://medium.com/@tonistiigi/advanced-multi-stage-build-patterns-6f741b852fae

### Kubernetes Credentialing Curriculum

#### Core Concepts
- Understand Kubernetes API primitives
  - https://kubernetes.io/docs/concepts/overview/working-with-objects/kubernetes-objects/#understanding-kubernetes-objects
- Create and configure basic Pods
  - https://kubernetes.io/docs/concepts/workloads/pods/pod-overview/
  
#### Configuration
- Understand ConfigMaps
  - https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/
- Understand SecurityContexts
  - https://kubernetes.io/docs/tasks/configure-pod-container/security-context/
- Define an application's resource requirements
  - https://kubernetes.io/docs/concepts/configuration/manage-compute-resources-container/
- Create & consume Secrets
  - https://kubernetes.io/docs/concepts/configuration/secret/
- Understand Service Accounts
  - https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/
  
#### Multi-Container Pods
- Understand Multi-Container Pod design patterns (e.g. ambassador, adapter,sidecar)
  - https://kubernetes.io/docs/concepts/cluster-administration/logging/
  - https://kubernetes.io/docs/tasks/access-application-cluster/communicate-containers-same-pod-shared-volume/
  - https://medium.com/@santhoz/nginx-sidecar-reverse-proxy-for-performance-http-to-https-redirection-in-kubernetes-dd9dbe2fd0c7
#### Observability
- Understand LivenessProbes and ReadinessProbes
  - https://kubernetes.io/docs/concepts/workloads/pods/pod-lifecycle/
  - https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-probes/
- Understand container logging
  - https://kubernetes.io/docs/concepts/cluster-administration/logging/
- Understand how to monitor applications in Kubernetes
  - 
- Understand debugging in Kubernetes
  - https://kubernetes.io/docs/tasks/debug-application-cluster/debug-application-introspection/

#### Pod Design
- Understand how to use Labels, Selectors, and Annotations
  - https://kubernetes.io/docs/concepts/overview/working-with-objects/labels/
- Understand Deployments and hot to perform rolling updates and rollbacks
  - https://kubernetes.io/docs/concepts/workloads/controllers/deployment/ 
- Understand Jobs and CronJobs
  - https://kubernetes.io/docs/concepts/workloads/controllers/jobs-run-to-completion/
  - https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/

#### Servics & Networking
- Understand Services
  - https://kubernetes.io/docs/concepts/services-networking/service/
- Demonstrate basic understanding of NetworkPolicies
  - https://kubernetes.io/docs/concepts/services-networking/network-policies/
- Ingress
  - https://kubernetes.io/docs/concepts/services-networking/ingress/

#### State Persistence
- Understand PersitentVolumeClaims for storage
  - https://kubernetes.io/docs/concepts/storage/dynamic-provisioning/

#### Azure Container Registry
Azure Container Registry is a managed Docker registry service based on the open-source Docker Registry 2.0. Create and maintain Azure container registries to store and manage your private Docker container images.

https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro

#### Development using Azure Container Instances

#### Azure AKS Dev Spaces
 With minimal dev machine setup, you can iteratively run and debug containers directly in Azure Kubernetes Service (AKS).  You can also collaborate with your team in a shared Kubernetes cluster, and do end-to-end testing with other components without replicating or mocking up dependencies. With Azure Dev Spaces, you can develop on Windows, Mac, or Linux using familiar tools like Visual Studio, Visual Studio Code, or the command line. 

https://docs.microsoft.com/en-us/azure/dev-spaces/

#### Draft

#### Brigade

#### Helm

#### VSCode Integrations




