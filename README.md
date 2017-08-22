# tmpld
[![Build Status](https://travis-ci.org/joeblackwaslike/debian.svg?branch=master)](https://travis-ci.org/joeblackwaslike/tmpld) [![Docker Pulls](https://img.shields.io/docker/pulls/joeblackwaslike/tmpld.svg)](https://hub.docker.com/r/joeblackwaslike/tmpld/) [![Github Repo](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/joeblackwaslike/tmpld)


## Maintainer
Joe Black | <me@joeblack.nyc> | [github](https://github.com/joeblackwaslike)


## Introduction
CLI tool combining jinja2 with parsers and other objects including Kubernetes
API objects and linux capabilities objects.


## Usage
```
usage: tmpld (sub-commands ...) [options ...] {arguments ...}

Base Controller

positional arguments:
  templates             template files to render

optional arguments:
  -h, --help            show this help message and exit
  --debug               toggle debug output
  --quiet               suppress all output
  -d DATA, --data DATA  file(s) containing context data
  -s, --strict          Raise an exception if a variable is not defined
```