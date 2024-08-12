# Flux at TXIT

To be expanded...

## Flux Structire

```
├── apps
│   ├── dagobah
│   │   ├── minio
│   │   │   └── conf
│   │   ├── renovate
│   │   │   └── conf
│   │   ├── vaultwarden
│   │   │   └── conf
│   │   └── zitadel
│   │       └── conf
│   └── venator
│       └── whoami
│           └── conf
├── clusters                # Fuga Cloud Managed Kubernetes AMS
│   ├── dagobah
│   │   ├── configs
│   │   ├── flux-system
│   │   └── sources
│   │       └── helm
│   ├── mandalore           # Fuga Cloud Managed Kubernetes FRA
│   │   ├── configs
│   │   ├── flux-system
│   │   └── sources
│   │       └── helm
│   └── venator             # K3S Cluster at home
│       ├── configs
│       ├── flux-system
│       └── sources
│           └── helm
├── infra
│   ├── dagobah
│   │   ├── certmanager
│   │   │   └── conf
│   │   ├── cloudnative-pg
│   │   │   └── conf
│   │   │       └── databases
│   │   │           ├── gitea
│   │   │           ├── juicefs
│   │   │           ├── vaultwarden
│   │   │           └── zitadel
│   │   ├── ingress-nginx
│   │   │   └── conf
│   │   └── juicefs
│   │       └── conf
│   └── venator
│       └── juicefs
│           └── conf
└── secrets
    ├── dagobah
    │   ├── cloudnative-pg
    │   ├── gitea
    │   ├── juicefs
    │   ├── minio
    │   ├── renovate
    │   ├── shared
    │   ├── vaultwarden
    │   └── zitadel
    ├── default
    └── venator
        ├── juicefs
        └── shared
```
