# HPING3

![logo](https://assets.gitlab-static.net/uploads/-/system/project/avatar/17010800/hping3.jpg)

## INDEX

- [HPING3](#hping3)
  - [INDEX](#index)
  - [BADGES](#badges)
  - [INTRODUCTION](#introduction)
  - [PREREQUISITES](#prerequisites)
  - [INSTALL](#install)
    - [DOCKER RUN](#docker-run)
    - [DOCKER COMPOSE](#docker-compose)
  - [LICENSE](#license)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/hping3/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/HPING3/commits/master)

## INTRODUCTION

Docker image of :

- [hping3](https://tools.kali.org/information-gathering/hping3)

Continuous integration on :

- [gitlab pipelines](https://gitlab.com/oda-alexandre/hping3/pipelines)

Automatically updated on :

- [docker hub public](https://hub.docker.com/r/alexandreoda/hping3)

## PREREQUISITES

Use [docker](https://www.docker.com)

## INSTALL

### DOCKER RUN

```\
docker  run -ti --rm --name hping3 alexandreoda/hping3
```

### DOCKER COMPOSE

```yml
version: "3.7"

services:
  hping3:
    container_name: hping3
    image: alexandreoda/hping3
    restart: no
    privileged: false
```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/hping3/blob/master/LICENSE)
