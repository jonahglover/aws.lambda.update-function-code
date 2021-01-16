[![Build Status](https://travis-ci.org/opspec-pkgs/aws.s3.cp-dir.svg?branch=master)](https://travis-ci.org/opspec-pkgs/aws.s3.cp-dir)

<img src="icon.svg" alt="icon" height="100px">

# Problem statement

updates a lambda function with a package from s3

# Format

the op uses [![opspec 0.1.5](https://img.shields.io/badge/opspec-0.1.5-brightgreen.svg?colorA=6b6b6b&colorB=fc16be)](https://opspec.io/0.1.5) definition format

# Example usage

## Install

```shell
opctl op install github.com/opspec-pkgs/aws.lambda.update-function-code
```

## Run

```
opctl run github.com/jonahglover/aws.lambda.update-function-code
```

## Compose

```yaml
op:
  ref: github.com/jonahglover/aws.lambda.update-function-code
  inputs:
    accessKeyId:
    secretAccessKey:
    srcS3Bucket:
    srcS3Key:
    dstLambdaFunctionName:
    # params w/ default
    region:
```