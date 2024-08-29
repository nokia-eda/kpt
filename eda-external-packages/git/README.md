# git

## Description
Dont have a git server ? This package launched two instances of the GOGS git server.

namely `eda-git` and `eda-git-replica`

## Usage

### Customization

The following kpt setters are available:

* `${GOGS_IMG_TAG}` - The Gogs image

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] git`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree git`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init git
kpt live apply git --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
