[![Docker Stars](https://img.shields.io/docker/stars/frolvlad/alpine-ruby.svg?style=flat-square)](https://hub.docker.com/r/frolvlad/alpine-ruby/)
[![Docker Pulls](https://img.shields.io/docker/pulls/frolvlad/alpine-ruby.svg?style=flat-square)](https://hub.docker.com/r/frolvlad/alpine-ruby/)


Ruby Docker image
=================

This image is based on Alpine Linux image, which is only a 5MB image, and contains
[Ruby 2.7](https://www.ruby-lang.org/).

This image is only 21MB on disk.


Usage Example
-------------

```bash
$ docker run --rm 2mia/alpine-ruby ruby -e 'puts "Hello World"'
```

Once you have run this command you will get printed 'Hello World' from Ruby!
