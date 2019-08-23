# Python 2.7, 3.4 & 3.5 App w/ Bureaucrat init support

This container uses [panubo/python](https://hub.docker.com/r/panubo/python/) which has the latest [Python](http://python.org) versions built from source.

This container is used to support runtime Python application deployment with the use of [voltgrid.py](https://github.com/voltgrid/voltgrid-pie) and [Bureaucrat](https://github.com/adlibre/python-bureaucrat).

An empty [virtualenv](https://github.com/pypa/virtualenv) is provided for each Python version.

Alternatively you can use this container as a base for your own Dockerfile.

## Example Projects

See [Voltgrid Django Example](https://github.com/voltgrid/voltgrid-django-example).

## Build

    make build

## Status

Deprecated. Please do not use this for new projects. If you require Bureaucrat
style process management then we recommend using the [Bash Container](https://github.com/panubo/bash-container/)
functions.
