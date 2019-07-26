# unity-keep-library-buildkite-plugin
Buildkite plugin for preserving asset library between builds

## To Use

Set these environmental variables:

```
# Optional

# Defaults to /tmp
CACHE_DIR

# Defaults to ""
# This is appended to ${BUILDKITE_BUILD_CHECKOUT_PATH} 
UNITY_PROJECT_PATH 

```

## TODO

  1. Convert env variable for setting the base dir to a porperty
