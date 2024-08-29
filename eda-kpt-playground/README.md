# eda-kpt-playground

## Description
This is a sample kpt package to bootstrap an install of eda

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] eda-kpt-playground`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree eda-kpt-playground`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init eda-kpt-playground
kpt live apply eda-kpt-playground --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
