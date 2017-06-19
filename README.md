# piweb
Docker images for CI built for Raspberry Pi 3

## Build images

1. `git clone https://github.com/golflima/piweb.git`
2. `cd piweb`
3. `git submodule update --init --recursive`
5. `./build`

## Use these images in your Dockerfiles

* `FROM golflima/piweb:php-5.5`
* `FROM golflima/piweb:php-5.6`
* `FROM golflima/piweb:php-7.0`
* `FROM golflima/piweb:php-7.1`

## What's inside?

* PHP, the version requested
* Node.js v6+
* Yarn
* Git
* Composer
* PHPunit
* PHPCS

See : https://github.com/TetraWeb/docker