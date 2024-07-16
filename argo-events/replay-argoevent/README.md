# replay-package

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] replay-package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree replay-package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init replay-package
kpt live apply replay-package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
