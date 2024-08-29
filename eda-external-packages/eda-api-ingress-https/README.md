# eda-api-ingress-https

## Description
Sample ingress config that connects to the eda-api service using HTTPS. The client connects to Ingress but Ingress always uses HTTPS to connect to the eda-api service.

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] eda-api-ingress-https`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree eda-api-ingress-https`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init eda-api-ingress-https
kpt live apply eda-api-ingress-https --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
