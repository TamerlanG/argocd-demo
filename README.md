# ArgoCD Playground

A simple playground repository for experimenting with ArgoCD and GitOps workflows. This repository contains basic configurations to help you get started with ArgoCD, including progressive delivery examples.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/argocd-demo.git
   cd argocd-demo
   ```

2. Create the ArgoCD app for whichever example your interested in.
   ```bash
   kubectl apply -f argocd/apps/blue-green.yaml
   ```

## Prerequisites

- Kubernetes cluster
- ArgoCD installed in your cluster
- kubectl configured to access your cluster
- Git