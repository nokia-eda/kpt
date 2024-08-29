# fluentd

## Description
A sample deployment of fluentd + bit to capture and aggregate logs

## Usage

### Customization:

The following kpt setters are available:

* `${FB_IMG}` - The fluentbit ds image
* `${FD_IMG}` - The fluentd deployment image

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] fluentd`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree fluentd`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init fluentd
kpt live apply fluentd --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
