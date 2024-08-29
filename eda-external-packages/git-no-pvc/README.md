# git-no-pvc

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] git-no-pvc`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree git-no-pvc`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init git-no-pvc
kpt live apply git-no-pvc --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
