# aws-mq-cleaner

[![License](https://img.shields.io/github/license/habx/aws-mq-cleaner)](/LICENSE)
[![Release](https://img.shields.io/github/release/habx/aws-mq-cleaner.svg)](https://github.com/habx/aws-mq-cleaner/releases/latest)
[![Docker](https://img.shields.io/docker/pulls/habx/aws-mq-cleaner)](https://hub.docker.com/r/habx/aws-mq-cleaner)
[![CircleCI](https://img.shields.io/circleci/build/github/habx/aws-mq-cleaner/dev)](https://app.circleci.com/pipelines/github/habx/aws-mq-cleaner)

## About

`aws-mq-cleaner` is a tool to remove sqs queues and sns topics that are no more used.


## Install

### Docker

```bash
docker pull habx/aws-mq-cleaner
docker container run --rm habx/aws-mq-cleaner --help
```

### Binary

#### MACOS

Set VERSION

```bash
VERSION=vx.x.x wget https://github.com/habx/aws-mq-cleaner/releases/download/${VERSION}/aws-mq-cleaner_darwin_amd64.gz
```

#### LINUX

```bash
VERSION=vx.x.x wget https://github.com/habx/aws-mq-cleaner/releases/download/${VERSION}/aws-mq-cleaner_linux_amd64.gz
```

### go source

```bash
go get -t github.com/habx/aws-mq-cleaner
aws-mq-cleaner --help
```

## Docs

[Docs](docs/aws-mq-cleaner.md)
