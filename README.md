# macos-preflight [![Build Status](https://travis-ci.org/tanakapayam/macos-preflight.svg?branch=master)](https://travis-ci.org/tanakapayam/macos-preflight)

## Motivation

`macos-preflight` checks the installation of modern scripting languages, package managers and packages that are not a part of a freshly-installed macOS on a MacBook Pro. Once these are in place, other packages can be installed readily.

## Run

```
$ ./macos-preflight
## Package Managers

* brew: found
* gem: found
* npm: found
* pip: found


## Version-Checking Tools

* semver: found
   * 5.5.0
* perl: found
   * 5.28.0


## Packages

* bash: found
* git: found
* gmake: found


## Versions

* bash: 4.4.23
* git: 2.18.0
* gmake: 4.2.1


Success!
```
