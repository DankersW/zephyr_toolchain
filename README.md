# Zephyr toolchain Docker image

Toolchain docker image for building Zephyr applications.

A new docker image is created via tags in the CI. Triggering the CI is either done in the github GUI by creating a tag with the format `"0.0.0"` or by creating a tag via the CLI and pushing it upstream.

```sh
git tag 0.0.0 -a -m "First release"
git push origin 0.0.0
```
