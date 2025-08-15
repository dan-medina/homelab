# Homelab Samba File Server on Ubuntu Server 24.04.3 LTS

A lightweight Ubuntu Server VM configured as a Samba file server with automated rsync backups.

## Features
- Samba file sharing
- Automated rsync backups to an external drive
- Secure remote access via OpenSSH
- Minimized Ubuntu Server with LVM for efficient storage
- BIND9 DNS server to handle hostname resolution on local network

## Hardware
- Host: AMD Ryzen 5 5600X, 32GB DDR4 RAM, 2TB SSD
- VM: 4GB RAM, 2 cores, 50GB, VMware

## Setup
1. [Base Ubuntu Installation](docs/installation.md)
2. [Network Configuration](docs/network.md)