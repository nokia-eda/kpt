# trust-manager

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] trust-manager`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree trust-manager`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init trust-manager
kpt live apply trust-manager --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
