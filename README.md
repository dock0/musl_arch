dock0/static_arch
=======

[![Automated Build](https://img.shields.io/docker/build/dock0/static_arch.svg)](https://hub.docker.com/r/dock0/static_arch/)
[![Build Status](https://img.shields.io/travis/com/dock0/static_arch.svg)](https://travis-ci.com/dock0/static_arch)
[![MIT Licensed](http://img.shields.io/badge/license-MIT-green.svg)](https://tldrlegal.com/license/mit-license)

A minimal Arch container with the [amylum](https://github.com/amylum/repo) repo added, built statically with [musl](http://www.musl-libc.org/)

## Usage

To build a new image, run `make -f MetaMakefile`. This launches the docker build container and builds a new image.

To start a shell in the build environment for manual actions, run `make manual`.

This image has pacman keys initialized.

## License

The scripts in this repo are released under the MIT License. See the bundled LICENSE file for details. The packages and other content stored in root.tar.xz retains its original licenses.

