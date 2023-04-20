# Helm-Charts
Continuously updated, the Helm Chart produced mainly includes a third-party official image

## adminer
Adminer Helm chart for Kubernetes

### Source Code

- <https://github.com/vrana/adminer>

### Values

| Key                   | Type   | Default              | Description |
| --------------------- | ------ | -------------------- | ----------- |
| affinity              | object | `{}`                 |             |
| config.design         | string | `""`                 |             |
| config.externalserver | string | `""`                 |             |
| config.plugins        | string | `""`                 |             |
| fullnameOverride      | string | `""`                 |             |
| image.pullPolicy      | string | `"IfNotPresent"`     |             |
| image.registry        | string | "docker.io"          |             |
| image.repository      | string | `"library/adminer"`  |             |
| image.tag             | string | `"4.8.1-standalone"` |             |
| nameOverride          | string | `""`                 |             |
| nodeSelector          | object | `{}`                 |             |
| replicaCount          | int    | `1`                  |             |
| resources             | object | `{}`                 |             |
| service.port          | int    | `80`                 |             |
| service.type          | string | `"NodePort"`         |             |
| service.annotations   | object | `{}`                 |             |
| tolerations           | list   | `[]`                 |             |
