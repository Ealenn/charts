
## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| application | object | `{"enable":{"environment":true,"host":true,"http":true,"request":true},"logs":{"ignore":{"ping":false}}}` | Echo-Server configuration |
| application.enable | object | `{"environment":true,"host":true,"http":true,"request":true}` | Enable and Disable Echo-Server Features |
| application.enable.environment | bool | `true` | Enable environment in response - Show environment variables |
| application.enable.host | bool | `true` | Enable request in response |
| application.logs | object | `{"ignore":{"ping":false}}` | Enable and Disable logs Features |
| application.logs.ignore.ping | bool | `false` | Don't log ping request on route `/ping` |
| fullnameOverride | string | `""` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"ealen/echo-server"` | https://hub.docker.com/r/ealen/echo-server |
| image.tag | string | `"0.2.0"` | https://github.com/Ealenn/Echo-Server/releases |
| imagePullSecrets | list | `[]` |  |
| ingress | object | `{"annotations":{},"enabled":false,"hosts":[{"host":"cluster.local","paths":["/"]}],"tls":[]}` | ingress configuration |
| ingress.annotations | object | `{}` | example `kubernetes.io/ingress.class: nginx` for Nginx Ingress |
| ingress.enabled | bool | `false` | Enable ingress |
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
| serviceAccount.name | string | `nil` |  |
| tolerations | list | `[]` |  |