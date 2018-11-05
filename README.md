Dockerlint Container
====================

[![Build Status](https://travis-ci.org/oxeva/dockerlint.svg?branch=master)](https://travis-ci.org/oxeva/dockerlint)

What is Dockerlint
------------------

Linting tool for Dockerfiles based on recommendations from
[Dockerfile Reference](https://docs.docker.com/engine/reference/builder/) and [Best practices for writing Dockerfiles](https://docs.docker.com/engine/userguide/eng-image/dockerfile_best-practices/) as of Docker 1.6.

GitHub project : [RedCoolBeans/dockerlint](https://github.com/RedCoolBeans/dockerlint)

Usage
-----

Sample of project scanning :

```sh
docker run --rm -v $PWD/Dockerfile:/Dockerfile oxeva/dockerlint
```

or :

```sh
docker run --rm -v $PWD:/project oxeva/dockerlint dockerlint -f /project/Dockerfile
```
