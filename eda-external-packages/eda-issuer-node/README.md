# eda-issuer-node

## Description
The eda node certificate issuer

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] eda-issuer-node`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree eda-issuer-node`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init eda-issuer-node
kpt live apply eda-issuer-node --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
