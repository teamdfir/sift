![Logo](https://images.contentstack.io/v3/assets/blt36c2e63521272fdc/blt3e371eacc79a3ca4/60a5393fe2db156d00f0b8ab/400x460_DFIR_SIFT.jpg)

This repository is used to track all issues for SIFT.

## AWS

These are the latest AMIs build from [sift-packer](https://github.com/sans-dfir/sift-packer)

**Note:** these are headless, as in no GUI, it installs the server variant of SIFT.

Built On: July 15th, 2021

```
us-east-1: ami-0b631d85f5e19c06f
us-east-2: ami-0df6f0b50a2b8a141
us-west-1: ami-06e36872a7ee6a39f
us-west-2: ami-0392e66bea0682fca
```

## Supported Distros

* 20.04 Ubuntu Desktop 
* 20.04 Ubuntu Server

### Deprecated / No Longer Supported

* 14.04 Ubuntu
* 16.04 Ubuntu

## Installation

The installation and setup process has been streamlined by the release of the [SIFT CLI](https://github.com/sans-dfir/sift-cli). Please follow these [instructions](https://github.com/sans-dfir/sift-cli#installation) to install the CLI tool.

### Manual 

If you are interested in contributing, testing or installing manually without using the CLI tool, please visit the [sift-salt](https://github.com/sans-dfir/sift-saltstack) repository.
