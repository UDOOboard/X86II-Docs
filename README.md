# UDOO X86 II Documentation

[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](https://github.com/UDOOboard/X86II-Docs/LICENSE)

Travis build status: [![Build Status](https://travis-ci.org/UDOOboard/X86II-Docs.svg?branch=master)](https://travis-ci.org/UDOOboard/X86II-Docs)

This repository contains the source code for the documentation hosted at [www.udoo.org/docs-x86II/](http://www.udoo.org/docs-x86II/).


## Build the documentation locally
On PHP7+ install XML and mbstring modules:

    sudo apt install php7.2 composer php7.2-xml php7.2-mbstring
    composer install

Then build the documentation with

    composer generate && cp -r img/ static/

To serve the documentation from a development webserver, run

    cd static && php -S localhost:8080
