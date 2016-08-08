# puppet-module-pdsh

[![Build Status](https://travis-ci.org/treydock/puppet-module-pdsh.png)](https://travis-ci.org/treydock/puppet-module-pdsh)

####Table of Contents

1. [Overview](#overview)
2. [Usage - Configuration options](#usage)
3. [Reference - Parameter and detailed reference to all options](#reference)
4. [Limitations - OS compatibility, etc.](#limitations)
5. [Development - Guide for contributing to the module](#development)
6. [TODO](#todo)
7. [Additional Information](#additional-information)

## Overview



## Usage

### pdsh

    class { 'pdsh': }

## Reference

### Classes

#### Public classes

* `pdsh`: Installs and configures pdsh.

#### Private classes

* `pdsh::install`: Installs pdsh packages.
* `pdsh::config`: Configures pdsh.
* `pdsh::params`: Sets parameter defaults based on fact values.

### Parameters

#### pdsh

#####`foo`

## Limitations

This module has been tested on:

* CentOS 6 x86_64

## Development

### Testing

Testing requires the following dependencies:

* rake
* bundler

Install gem dependencies

    bundle install

Run unit tests

    bundle exec rake test

If you have Vagrant >= 1.2.0 installed you can run system tests

    bundle exec rake beaker

## TODO

## Further Information

*
