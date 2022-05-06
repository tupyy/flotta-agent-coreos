# Fedora CoreOS EdgeDevice 

This repo contains ignition file to install **flotta-agent** on Fedora CoreOS.

## Prerequisites

Export certificates with `make get-certs` and copy them to `files` folder.
If you want to have ssh access you need to copy the public key to `ign` file.

## Commands

- `make deploy` is creating a FCOS instance and deploying `flotta-agent`
- `make destroy` destroy the vm
- `make clean` clean the temporary files

### Remark

Inspired from a great repo: https://github.com/deuill/coreos-home-server
