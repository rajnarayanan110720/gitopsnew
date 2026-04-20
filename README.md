k8s/
├── base/
│   └── frontend/
│       ├── deployment.yaml
│       ├── service.yaml
│       ├── ingress.yaml
│       ├── hpa.yaml
│       ├── pdb.yaml
│       ├── configmap.yaml
│       ├── secret.yaml
│       └── kustomization.yaml
│
├── overlays/
│   ├── dev/
│   │   └── frontend/
│   │       ├── kustomization.yaml
│   │       └── patch-service.yaml
│   │
│   ├── stage/
│   │   └── frontend/
│   │       └── kustomization.yaml
│   │
│   └── prod/
│       └── frontend/
│           ├── kustomization.yaml
│           └── patch-ingress.yaml
