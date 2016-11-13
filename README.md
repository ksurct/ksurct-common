# ksurct-common
The KSURCT general purpose libraries.

This package provides `ksurct.common` and contains code that is expected to
be useful across years.

# Quick start
## Dependencies
This package is meant to be a dependency itself.

This package expects to be used with python3.5 or greater. Be sure to install python and it's
development headers.

```shell
sudo apt install python3.5 python3.5-venv python3.5-dev
```

Create a virtualenv. This will isolate python from the rest of the system so
that the system does not get too messy.

```shell
python3 --version  # at least Python 3.5.2
python3 -m venv venv
source venv/bin/activate # this needs to happen everytime you start a terminal.
```

## Install
This library is designed to be installed in other projects.

```shell
# Be sure to be in a virtualenv
pip install -e path_to_this_repo
```
