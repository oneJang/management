# video-argoevent

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] video-argoevent`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree video-argoevent`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init video-argoevent
kpt live apply video-argoevent --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
