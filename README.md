# gitops
``` .
├── README.md
├── apps
│   ├── base
│   │   └── frontend
│   └── patch
│       ├── dev
│       └── prod
├── argocd
│   ├── dev.yaml
│   ├── infra.yaml
│   └── prod.yaml
├── infra
│   ├── argocd-config
│   │   ├── argocd-cm-patch.yaml
│   │   └── kustomization.yaml
│   ├── kube-prometheus-stack
│   │   ├── charts
│   │   ├── kustomization.yaml
│   │   └── values.yaml
│   ├── kustomization.yaml
│   └── opensearch
└── root-app.yaml```