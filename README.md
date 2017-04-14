# SANS Investigative Forensic Toolkit (SIFT)

This repository is used to track all issues for SIFT.

## Important 

SIFT is moving to using `Salt` for configuration management of the SIFT VM. This is being coordinated with a similar effort for REMnux so that the two distributions will be compatible and not conflict with each other.

If you are interested in contributing or testing out this new installation method, please visit the [sift-salt](https://github.com/sans-dfir/sift-saltstack) repository.

## Legacy Install and Update Method

Currently the old method of install and update via a bash script is still available https://github.com/sans-dfir/sift-bootstrap.

## Roadmap

These are somewhat in order by priority.

* [x] Use Saltstack to build and perform updates to any SIFT installation (https://github.com/sans-dfir/sift-saltstack) https://github.com/sans-dfir/sift/issues/114
  * [ ] Be compatible with the REMnux installation (a similar effort is happening to make it use Saltstack (https://github.com/remnux/salt-states)
* [ ] Use Packer to build VMWare/Virtualbox/Cloud images using the [salt states](https://github.com/sans-dfir/sift-saltstack) https://github.com/sans-dfir/sift/issues/116
* [x] Use CI provider to do tests
  * [x] Each salt state should be testable and cross dependencies should be setup appropriately
  * [ ] Each salt state should include application specific testing (where possible) (ie. volatility)
* [ ] VMs should be published at least weekly
* [ ] Build CLI tool to download, verify, and run salt states on VM (@ekristen is building a prototype right now that will use GitHub releases and signatures to verify salt state downloads for both SIFT and REMnux)
