# BitBucket Pipelines Azure CLI

Ryosuke Goto

## Overview

This base image enable Azure CLI on Bitbucket Pipelines continuous integration/deployment.

## Usage

Specify this images in bitbucket-pipelines.yml

```
image: pathtrk/bitbucket-pipelines-azurecli:latest
```

## Notice

Azure CLI is installed by Python2.7 on this image.


## License

MIT