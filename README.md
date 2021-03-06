## Dockerfile: Debian - PHP-CLI (PHP 5)

[![Build Status](https://travis-ci.org/ericmdev/php5-cli.dockerfile.svg?branch=master)](https://travis-ci.org/ericmdev/php5-cli.dockerfile)

**Dockerfile** of [Debian](https://www.debian.org/) [PHP-CLI (PHP 5)](https://secure.php.net/):

- php5-common
- php5-cli

*Requirements*
- [Docker](https://www.docker.com/) 

*Base Docker Image*
- [ericmdev/essentials](https://hub.docker.com/r/ericmdev/essentials/)

*Docker Pull Command*
- `docker pull ericmdev/php5-cli`

### Usage

Build the image.

    $ make

Run the container.

    $ make run

Dig into the container.

    $ make exec

*See the `Makefile` for more options.