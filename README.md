# make-home-links readme

Simplify your shell setup by making symlinks to your home folder.

It takes a TOML file and creates symlinks from your checkout.

## Prerequisites

* `pipx` or just `pip3`

## Installation

One of:

* `pipx install make-home-links`
* `pip install --user make-home-links`

Upgrading:

* `pipx upgrade make-home-links`
* `pip install --user -U make-home-links`

After installation, `make-home-links` command should become available:

```shell
make-home-links --help
make-home-links --version
```

## Development

The project uses [`hatch`](https://hatch.pypa.io/) behind the scenes.

### How to use

```shell
# reformat the code
make fmt

# run the cli
hatch run cli

# run the cli version
hatch run cli --version

# run the cli help
hatch run help
hatch run cli --help

# run mypy
hatch run types:check

# run tests
hatch run test
hatch run test -k usual_pytest_flags -m my_marker

# go to the dev shell
hatch shell

# build the distribution
hatch build
```

### Increase version
```shell
hatch version <new_version>
```
