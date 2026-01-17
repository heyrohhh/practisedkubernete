# KubeMastery-Labs ☸️
### Comprehensive Kubernetes Hands-on Infrastructure Practice

This repository serves as a technical laboratory for mastering **Kubernetes (K8s) orchestration**. It contains practical implementations of container orchestration patterns, service discovery, and resource management strategies.

[![K8s Version](https://img.shields.io/badge/Kubernetes-v1.28%2B-blue?logo=kubernetes)](https://github.com/heyrohhh/practisedkubernete)

## 🚀 Technical Core Concepts
I have implemented the following cloud-native patterns within this project:

- **Workload Management:** Deploying scalable `Deployments` and individual `Pods` with health checks.
- **Service Discovery:** Implementing `ClusterIP`, `NodePort`, and `LoadBalancer` services for internal and external traffic management.
- **Configuration Management:** Using `ConfigMaps` and `Secrets` to decouple configuration from container images.
- **Storage & Persistence:** Managing data lifecycle using `PersistentVolumes (PV)` and `PersistentVolumeClaims (PVC)`.
- **Scaling & Self-Healing:** Configuring Horizontal Pod Autoscalers (HPA) and resource limits (CPU/Memory).

## 📁 Repository Structure
```plaintext
.
├── deployments/       # YAML manifests for application workloads
├── services/          # Networking and Load Balancing configurations
├── config-maps/       # Environment-specific configuration files
├── scripts/           # Helper scripts for minikube/kubectl setup
└── README.md          # Technical documentation
🛠️ Prerequisites & Setup
To run these manifests locally, ensure you have a cluster running (Minikube/Docker Desktop/K3s).

Clone the Labs:

Bash

git clone [https://github.com/heyrohhh/practisedkubernete.git](https://github.com/heyrohhh/practisedkubernete.git)
cd practisedkubernete
Apply Manifests:

Bash

kubectl apply -f deployments/
kubectl apply -f services/
Verify Status:

Bash

kubectl get all
💡 Why this Repo? (DevOps Perspective)
As an aspiring DevOps Engineer, I built this to demonstrate proficiency in:

YAML manifest writing and validation.

Understanding of K8s Networking and inter-pod communication.

Managing Stateful vs Stateless applications in a cluster.

Maintained by: [Your Name]
