# fluent-operator

## Description
sample description

## Usage

The following kpt setters are available:

* `${FO_FB_IMG}` - The fluentbit ds image
* `${FO_FC_IMG}` - The fluentbit deployment image
* `${FO_IMG}` - The fluentbit operator image

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] fluent-operator`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree fluent-operator`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init fluent-operator
kpt live apply fluent-operator --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
