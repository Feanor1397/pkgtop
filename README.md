
![Logo](https://user-images.githubusercontent.com/24392180/63693894-dd110e00-c81d-11e9-8f51-e00d5bd7d6a6.png)

# pkgtop [![Release](https://img.shields.io/github/release/keylo99/pkgtop.svg?style=flat-square)](https://github.com/keylo99/pkgtop/releases)
[![AUR](https://img.shields.io/aur/version/pkgtop-git.svg?style=flat-square)](https://aur.archlinux.org/packages/pkgtop-git/)
[![Travis Build](https://img.shields.io/travis/keylo99/pkgtop.svg?style=flat-square)](https://travis-ci.org/keylo99/pkgtop) [![Docker Build](https://img.shields.io/docker/cloud/build/keylo99/pkgtop.svg?style=flat-square)](https://hub.docker.com/r/keylo99/pkgtop/builds) [![Codacy Badge](https://img.shields.io/codacy/grade/f83f3a6b0bb042f39f799cb372405094.svg?style=flat-square)](https://www.codacy.com/app/keylo99/pkgtop?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=keylo99/pkgtop&amp;utm_campaign=Badge_Grade) [![Go Report Card](https://goreportcard.com/badge/github.com/keylo99/pkgtop?style=flat-square)](https://goreportcard.com/report/github.com/keylo99/pkgtop) [![Stars](https://img.shields.io/github/stars/keylo99/pkgtop.svg?style=flat-square)](https://github.com/keylo99/pkgtop/stargazers) [![License](https://img.shields.io/github/license/keylo99/pkgtop.svg?color=blue&style=flat-square)](./LICENSE)

pkgtop is an interactive package manager and resource monitor tool designed for the GNU/Linux.

## Installation

### • Dependencies
* [gizak/termui](https://github.com/gizak/termui/)
* [atotto/clipboard](https://github.com/atotto/clipboard)

### • AUR ([pkgtop-git](https://aur.archlinux.org/packages/pkgtop-git))

### • Manual Insallation

```
go get ./...
go build src/pkgtop.go
sudo mv pkgtop /usr/local/bin/
```
Preferably, [go install](https://golang.org/cmd/go/#hdr-Compile_and_install_packages_and_dependencies) command can be used.

## Command-Line Arguments
```
-h, show help message
-d, select linux distribution
-s, sort packages alphabetically
-v, print version
```

## Usage

...

## Screenshots

![Fedora Screenshot](https://user-images.githubusercontent.com/24392180/63657577-596b0900-c7ac-11e9-9bc3-834f31c557fd.png)

![Manjaro Screenshot](https://user-images.githubusercontent.com/24392180/63648224-2b96ad80-c735-11e9-86c8-5870c82c9554.png)

![Mint Screenshot](https://user-images.githubusercontent.com/24392180/63657582-6d166f80-c7ac-11e9-9174-1009daf62db0.png)

![Debian Screenshot](https://user-images.githubusercontent.com/24392180/63657584-769fd780-c7ac-11e9-8206-0d0a029d1c91.png)

![Ubuntu Screenshot](https://user-images.githubusercontent.com/24392180/63650076-2cd4d400-c74f-11e9-8435-55ee42dbfc33.png)

## Todo(s)
* Add 'paste' feature

## License

GNU General Public License v3. (see [gpl](https://www.gnu.org/licenses/gpl.txt))

## Credit

Copyright (C) 2019 by [keylo99](https://www.github.com/keylo99)