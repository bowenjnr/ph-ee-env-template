# ph_ee_connector_ams_mifos

![Version: 1.0.0](https://img.shields.io/badge/Version-1.0.0-informational?style=flat-square) ![AppVersion: 1.0.0](https://img.shields.io/badge/AppVersion-1.0.0-informational?style=flat-square)

ph_ee_connector_ams_mifos

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| SPRING_PROFILES_ACTIVE | string | `""` |  |
| ams_local_account_host | string | `"https://fynams.sandbox.mifos.io"` |  |
| ams_local_auth_host | string | `"https://fynams.sandbox.mifos.io"` |  |
| ams_local_customer_host | string | `"https://fynams.sandbox.mifos.io"` |  |
| ams_local_enabled | bool | `true` |  |
| ams_local_interop_host | string | `"https://fynams.sandbox.mifos.io"` |  |
| ams_local_loan_host | string | `"https://fynams.sandbox.mifos.io/"` |  |
| configmap.apiversion | string | `"v1"` |  |
| deployment.annotations.deployTime | string | `"{{ .Values.deployTime }}"` |  |
| deployment.apiVersion | string | `"apps/v1"` |  |
| dfspids | string | `"gorilla,rhino"` |  |
| enabled | bool | `true` |  |
| extraInitContainers | string | `""` |  |
| hostname | string | `"amsmifos.sandbox.mifos.io"` |  |
| image | string | `""` |  |
| imagePullPolicy | string | `"Always"` |  |
| imageTag | string | `"latest"` |  |
| ingress.annotations."kubernetes.io/ingress.class" | string | `"nginx"` |  |
| ingress.apiversion | string | `"networking.k8s.io/v1"` |  |
| ingress.backend.service.name | string | `"ph-ee-connector-ams-mifos"` |  |
| ingress.backend.service.port.number | int | `80` |  |
| ingress.enabled | bool | `true` |  |
| ingress.path | string | `"/"` |  |
| ingress.tls[0].hosts | string | `"amsmifos.sandbox.mifos.io"` |  |
| ingress.tls[1].secretName | string | `"sandbox-secret"` |  |
| keycloak.enabled | bool | `true` |  |
| limits.cpu | string | `"500m"` |  |
| limits.memory | string | `"512M"` |  |
| operations_app.datasource.host | string | `"operationsmysql"` |  |
| requests.cpu | string | `"100m"` |  |
| requests.memory | string | `"256M"` |  |
| secret.apiversion | string | `"v1"` |  |
| service.apiversion | string | `"v1"` |  |
| wildcardhostname | string | `"amsmifos.sandbox.mifos.io"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.11.0](https://github.com/norwoodj/helm-docs/releases/v1.11.0)