# eda-core-namespace

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] eda-core-namespace`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree eda-core-namespace`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init eda-core-namespace
kpt live apply eda-core-namespace --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
