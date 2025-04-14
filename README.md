# ArgoCD Playground

A simple playground repository for experimenting with ArgoCD and GitOps workflows. This repository contains basic configurations to help you get started with ArgoCD.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/argocd-demo.git
   cd argocd-demo
   ```

2. Apply the ArgoCD project configuration:
   ```bash
   kubectl apply -f argocd/project.yaml
   ```

3. Create the ArgoCD application:
   ```bash
   kubectl apply -f argocd/app.yaml
   ```

## Prerequisites

- Kubernetes cluster
- ArgoCD installed in your cluster
- kubectl configured to access your cluster
- Git