# Picolors

> Extract prominent colors from an image

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"ealen/picolors"` | https://hub.docker.com/r/ealen/picolors |
| image.tag | string | `"0.1.0"` | https://github.com/Ealenn/Picolors/releases |
| imagePullSecrets | list | `[]` |  |
| ingress.annotations | object | `{}` | Example `kubernetes.io/ingress.class: nginx` for Nginx Ingress |
| ingress.enabled | bool | `false` | Enable ingress |
| ingress.hosts[0].host | string | `"cluster.local"` |  |
| ingress.hosts[0].paths[0] | string | `"/"` |  |
| ingress.tls | list | `[]` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| podSecurityContext | object | `{}` |  |
| replicaCount | int | `1` | number of pod replicas |
| resources.limits.cpu | string | `"50m"` |  |
| resources.limits.memory | string | `"32Mi"` |  |
| resources.requests.cpu | string | `"50m"` |  |
| resources.requests.memory | string | `"32Mi"` |  |
| securityContext | object | `{}` |  |
| service.port | int | `80` |  |
| service.type | string | `"ClusterIP"` |  |
| serviceAccount.create | bool | `true` |  |
| serviceAccount.name | string | `""` |  |
| tolerations | list | `[]` |  |
