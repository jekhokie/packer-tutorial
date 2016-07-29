# Packer Tutorial

This repository is a basic project demonstrating the Packer tool (https://www.packer.io/).

## Prerequisites

Make sure the following tools are installed and/or available:

* Packer
* VirtualBox
* Vagrant (version 1.8.5+ - used for testing the Vagrant box created)

### Notes

In Vagrant versions prior to 1.8.5, attempting to boot an Ubuntu 16.04 image results in
an error related to identifying the network interface of the VM incorrectly as eth1.

## Run

To run the build for a VirtualBox VM (Ubuntu 16.04 at the time of this writing):

```bash
packer build ubuntu16_64.json
```
