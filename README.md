[![Build Status](https://travis-ci.com/sebastianzillessen/docker-node-chrome.svg?branch=master)](https://travis-ci.com/sebastianzillessen/docker-node-chrome)
# docker-node-chrome

> forked from [amio/docker-node-chrome](https://github.com/amio/docker-node-chrome)

Dockerfile for nodejs + chrome.

## On docker hub

https://hub.docker.com/r/sebzill/node-chrome/

This [Dockerfile](/Dockerfile) contains:

### Versions

| Build     | Node      | NPM   | Google Chrome |
| -----     | -----     | ----- | -----         |
| latest    |10.13.0    | 6.4.1 | 72.0.3626.109  |
| 1.0.1     |10.13.0    | 6.4.1 | 70.0.3538.110  |

It is ready to run e.g. protractor tests.

## Development

Build image:
```
docker build -t sebzill/node-chrome .
```
On changes, there is a [TravisJob](https://travis-ci.com/sebastianzillessen/docker-node-chrome) validating the build.

In addition, DockerHub will build from master the latest version. All Tags will be build as new version as well.

## Lincense

MIT @ [Amio](https://github.com/amio)
