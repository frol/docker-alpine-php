[![Docker Stars](https://img.shields.io/docker/stars/frolvlad/alpine-php.svg?style=flat-square)](https://hub.docker.com/r/frolvlad/alpine-php/)
[![Docker Pulls](https://img.shields.io/docker/pulls/frolvlad/alpine-php.svg?style=flat-square)](https://hub.docker.com/r/frolvlad/alpine-php/)


PHP Docker image
================

This image is based on Alpine Linux image, which is only a 5MB image, and contains
[PHP](http://php.net/) programming language.

This image is only 17MB on disk.

NOTE: This image is not really intended for a site hosting use-case. It is
created to run pure PHP code from a shell.


Usage Example
-------------

```bash
$ docker run --rm frolvlad/alpine-php php -r 'echo "Hello World";'
```

Once you have run this command you will get printed 'Hello World' from PHP!
