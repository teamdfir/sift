![Logo](https://images.contentstack.io/v3/assets/blt36c2e63521272fdc/blt3e371eacc79a3ca4/60a5393fe2db156d00f0b8ab/400x460_DFIR_SIFT.jpg)

This repository is used to track all issues for SIFT.

## AWS

These are the latest AMIs build from [sift-packer](https://github.com/sans-dfir/sift-packer)

**Note:** these are headless, as in no GUI, it installs the server variant of SIFT.

Built On: March 2nd, 2022

**Default User:** `sansforensics`

```
ap-northeast-1: ami-00378014d524eee9c
ap-northeast-2: ami-06408b1c23cad3f8b
ap-northeast-3: ami-0cf5998c0f77e349d
ap-southeast-1: ami-0db8ec4279e4f27ca
ap-southeast-2: ami-04c740d52b4a32959
eu-central-1: ami-06535b5a0f7d99f4c
eu-north-1: ami-049c42f0a1ea82701
eu-west-1: ami-01f1035b96448b73b
eu-west-2: ami-0407016f8aa79ea7c
eu-west-3: ami-0c444654c3cb65700
us-east-1: ami-0d52daefbb3dad017
us-east-2: ami-08faa4091f9e4121d
us-west-1: ami-0bf84579f13473e79
us-west-2: ami-0b9d5c33ff8f8ca7d
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
