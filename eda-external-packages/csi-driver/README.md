# csi-driver

## Description
A KPT package to deploy csi-driver v1.14.4

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] csi-driver`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree csi-driver`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init csi-driver
kpt live apply csi-driver --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
