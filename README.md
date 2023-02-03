<img align="right" src="https://images.contentstack.io/v3/assets/blt36c2e63521272fdc/blt3e371eacc79a3ca4/60a5393fe2db156d00f0b8ab/400x460_DFIR_SIFT.jpg" />

# SIFT

This is a metadata repository that is primarily used for discussiosn and issue tracking. 

- [cast](https://github.com/ekristen/cast) -- installer cli
- [saltstack](https://github.com/teamdfir/sift-saltstack) -- states that actually do the work
- [packer](https://github.com/teamdfir/sift-packer) -- builds machine images using the above tools
- [package-scripts](https://github.com/teamdfir/package-scripts) -- builds certain packages hosted in [SIFT PPA](https://launchpad.net/~sift)

## Supported Distros

* 20.04 Ubuntu (Focal)
* 22.04 Ubuntu (Jammy)

## Installation

[Cast](https://github.com/ekristen/cast) is the replacement to the [SIFT CLI](https://github.com/sans-dfir/sift-cli). While the SIFT CLI should continue to work it is officially deprecated as of March 1, 2023 and will no longer be guaranteed to work after that date.

You must first install the CLI tool, then you can install SIFT.

```console
sudo cast install teamdfir/sift-saltstack
```

## Cloud Providers

### AWS

These are the latest AMIs build from [sift-packer](https://github.com/sans-dfir/sift-packer)

**Note:** these are headless, as in no GUI, it installs the server variant of SIFT.

### 22.04 Jammy Images

**Coming Soon**

### 20.04 Focal Images

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

