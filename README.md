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
opctl run github.com/opspec-pkgs/aws.lambda.update-function-code
```

## Compose

```yaml
op:
  ref: github.com/jonahglover/aws.lambda.update-function-code
  inputs:
    accessKeyId:
    dstS3Uri:
    secretAccessKey:
    srcS3Uri:
    # params w/ default
    region:
```

# Support

join us on
[![Slack](https://opctl-slackin.herokuapp.com/badge.svg)](https://opctl-slackin.herokuapp.com/)
or
[open an issue](https://github.com/opspec-pkgs/aws.s3.cp-dir/issues)

# Releases

releases are versioned according to
[![semver 2.0.0](https://img.shields.io/badge/semver-2.0.0-brightgreen.svg)](http://semver.org/spec/v2.0.0.html)
and [tagged](https://git-scm.com/book/en/v2/Git-Basics-Tagging); see
[CHANGELOG.md](CHANGELOG.md) for release notes

# Contributing

see
[project/CONTRIBUTING.md](https://github.com/opspec-pkgs/project/blob/master/CONTRIBUTING.md)
