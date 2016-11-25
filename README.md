# dockerized-docs-rundeck

# What is it?#
Dockerzied Rundeck documentation for offline use.

# Image description #
Base image: `httpd:2.4.23`.
The most current rundeck `master` branch is cloned and built using Pandoc document converter.
Rundeck ocumentation directory (`/rundeck/docs/en/dist/html`) is linked to httpd `DocumentRoot` (`/usr/local/apache2/htdocs`).

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-rundeck

```

You can test it by visiting http://container-ip:80
