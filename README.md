# Temperature converter application - GitOps Repository

This repo contains the Helm chart for the Temperature converter application. It is deployed using GitOps.

Following are the contents of the Helm Chart:
```
├── Chart.yaml
├── LICENSE
├── README.md
├── charts
├── templates
│   ├── NOTES.txt
│   ├── _helpers.tpl
│   ├── deployment.yaml
│   ├── hpa.yaml
│   ├── ingress.yaml
│   ├── rbac.yaml
│   ├── route.yaml
│   ├── service.yaml
│   ├── serviceaccount.yaml
│   └── tests
│       └── test-connection.yaml
└── values.yaml

3 directories, 14 files
```