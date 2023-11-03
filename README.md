# Apidoc Docker Image

[![Docker Image CI](https://github.com/chinayin-docker/apidoc/actions/workflows/ci.yml/badge.svg?event=schedule)](https://github.com/chinayin-docker/apidoc/actions/workflows/ci.yml)
![Docker Image Version (latest semver)](https://img.shields.io/docker/v/chinayin/apidoc?sort=semver)
![Docker Image Size (latest semver)](https://img.shields.io/docker/image-size/chinayin/apidoc?sort=semver)
![Docker Pulls](https://img.shields.io/docker/pulls/chinayin/apidoc)

RESTful web API Documentation Generator.

### Supported tags and respective `Dockerfile` links

![](https://img.shields.io/docker/v/chinayin/apidoc/latest)

### Image Variants

- `apidoc:<version>`

### Usage

You can use the image directly, e.g.

```
docker run --rm -it chinayin/apidoc:latest
```

The images are built daily and have the security release enabled, so will contain any security updates released more
than 24 hours ago.

You can also use the images as a base for your own Dockerfile:

```
FROM chinayin/apidoc:latest
```
