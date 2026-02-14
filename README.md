# Nextcloud php-FPM Docker images

[![Author][ico-bluesky]][link-bluesky]
[![Build Status][ico-ghactions]][link-ghactions]
[![Docker Pull][ico-docker]][link-docker]
[![Latest Version][ico-version]][link-docker]
[![Software License][ico-license]](LICENSE)

Repository with my php-fpm Dockerfile for my Docker/Podman images.

## Debian based php-fpm Docker image for Nextcloud

Available for:

* PHP 8.5
* PHP 8.4

[System requirements](https://docs.nextcloud.com/server/latest/admin_manual/installation/system_requirements.html) for Nexcloud in the official documentation:

* 8.2 (deprecated)
* 8.3
* 8.4 (recommended)
* 8.5

## PHP 8.5

Usage:

```bash
docker pull llaumgui/nextcloud-php:8.5-fpm
```

or:

```bash
docker pull ghcr.io/llaumgui/nextcloud-php:8.5-fpm
```

And see [documentation](https://github.com/llaumgui/docker-images-nextcloud-php-fpm/tree/main/8.5).

## PHP 8.4

Usage:

```bash
docker pull llaumgui/nextcloud-php:8.4-fpm
```

or:

```bash
docker pull ghcr.io/llaumgui/nextcloud-php:8.4-fpm
```

And see [documentation](https://github.com/llaumgui/docker-images-nextcloud-php-fpm/tree/main/8.4).

[ico-bluesky]: https://img.shields.io/static/v1?label=Author&message=llaumgui&color=208bfe&logo=bluesky&style=flat-square
[link-bluesky]: https://bsky.app/profile/llaumgui.kulakowski.fr
[ico-docker]: https://img.shields.io/docker/pulls/llaumgui/nextcloud-php?color=%2496ed&logo=docker&style=flat-square
[link-docker]: https://hub.docker.com/r/llaumgui/nextcloud-php
[ico-ghactions]: https://img.shields.io/github/actions/workflow/status/llaumgui/docker-images-nextcloud-php-fpm/devops.yml?label=DevOps&logo=github&style=flat-square
[link-ghactions]: https://github.com/llaumgui/docker-images-nextcloud-php-fpm/actions
[ico-version]: https://img.shields.io/docker/v/llaumgui/nextcloud-php?sort=semver&color=%2496ed&logo=docker&style=flat-square
[ico-license]: https://img.shields.io/github/license/llaumgui/docker-images-nextcloud-php-fpm?style=flat-square
