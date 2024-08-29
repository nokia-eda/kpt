# eda-api-ingress-https-passthrough

## Description
Sample Ingress definition for HTTPS passthrough to the eda-api service. Read more at https://kubernetes.github.io/ingress-nginx/user-guide/tls/#ssl-passthrough

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] eda-api-ingress-https-passthrough`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree eda-api-ingress-https-passthrough`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init eda-api-ingress-https-passthrough
kpt live apply eda-api-ingress-https-passthrough --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
