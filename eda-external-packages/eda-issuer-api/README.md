# eda-issuer-api

## Description
The eda-api frontend certificate issuer

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] eda-issuer-api`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree eda-issuer-api`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init eda-issuer-api
kpt live apply eda-issuer-api --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
