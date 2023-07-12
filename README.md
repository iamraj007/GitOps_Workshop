# GitOps_Workshop

GitOps workshop with ArgoCD

This repo contain a ArgoCD Application that will deploy a simple kubernetes apps with kustomize.

Please find the overall structure of app in datails below for overview:

```
└── mynginx-app
    ├── base
    │   ├── deployment.yaml
    │   ├── kustomization.yaml
    │   └── service.yaml
    └── overlays
        └── test
            ├── deployment_gitops_app.yaml
            ├── kustomization.yaml
            ├── ns.yaml
            └── replica-and-rollout-strategy.yaml
```
