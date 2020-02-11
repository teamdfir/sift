**Note: As of January 2020, new installs of SIFT on 16.04 is currently broken due to the removal of Plaso's builds for 16.04. Please use 18.04 if possible.**

![Logo](https://digital-forensics.sans.org/images/sift.png)

This repository is used to track all issues for SIFT. 

## Installation

The installation and setup process has been streamlined by the release of the [SIFT CLI](https://github.com/sans-dfir/sift-cli). Please follow these [instructions](https://github.com/sans-dfir/sift-cli#installation) to install the CLI tool.

### Manual 

If you are interested in contributing, testing or installing manually without using the CLI tool, please visit the [sift-salt](https://github.com/sans-dfir/sift-saltstack) repository.

### Bootstrap (Fully Deprecated)

This method is no longer supported. The [repository](https://github.com/sans-dfir/sift-bootstrap) has been left for legacy reasons and a way to let everyone know it is no longer supported.

## Roadmap

* [ ] VMs should be published at least monthly (or more frequently)
* [x] Be compatible with the REMnux installation (a similar effort is happening to make it use Saltstack (https://github.com/remnux/salt-states)
* [x] Use Packer to build VMWare/Virtualbox/Cloud images using the [salt states](https://github.com/sans-dfir/sift-saltstack) https://github.com/sans-dfir/sift/issues/116
* [x] Use CI provider to do tests
  * [x] Each salt state should be testable and cross dependencies should be setup appropriately
  * [ ] Each salt state should include application specific testing (where possible) (ie. volatility)
* [x] Use Saltstack to build and perform updates to any SIFT installation (https://github.com/sans-dfir/sift-saltstack) https://github.com/sans-dfir/sift/issues/114
* [x] Build CLI tool to download, verify, and run salt states on VM (@ekristen is building a prototype right now that will use GitHub releases and signatures to verify salt state downloads for both SIFT and REMnux)
