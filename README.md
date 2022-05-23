# Fedora CoreOS EdgeDevice 

This repo contains ignition file to install **flotta-agent** on Fedora CoreOS.

## Prerequisites

Export certificates with `make get-certs` and copy them to `files` folder.
If you want to have ssh access you need to copy the public key to `ign` file.

## Commands

- `make deploy` is creating a FCOS instance with the default vm name and deploying `flotta-agent`. If you want to use another name just set `VM_NAME=<instance_name> make deploy`.
- `make destroy` destroy the vm
- `make clean` clean the temporary files

### Remark

Inspired from a great repo: https://github.com/deuill/coreos-home-server
