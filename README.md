# ISEA Server Labs

Lab documentation for BRG27-ISEA: Introduction to Server Environments and Architectures.

## About

This is about the labs i have completed over the past 3 weeks and what i had to do differently to fix issues that come up


## Environment

- Host machine: MACBOOK AIR (M2)
- Virtualisation: UTM
- Guest OS: Ubuntu 24.04 ARM64
- Cloud platform: AWS EC2, Ubuntu

## Labs

| Lab | Topic | Folder | Status |
| --- | --- | --- | --- |
| 1a-1 | Obtaining a Linux environment | `1a-1-obtaining-linux/` | Done |
| 1a-2 | Ubuntu familiarisation | `1a-2-ubuntu-familiarisation/` | Done |
| 1b-1 | Linux services | `1b-1-linux-services/` | Done |
| 1b-2 | Linux permissions | `1b-2-linux-permissions/` | Done |
| 1b-3 | File system search | `1b-3-file-system-search/` | To do |
| 2a-1 | TCO comparison | `2a-1-tco-comparison/` | To do |
| 2b-1 | AWS EC2 deployment | `2b-1-aws-ec2/` | To do |
| 2b-2 | Bash scripting and regex | `2b-2-bash-scripting/` | To do |
| 3a-1 | DNS configuration | `3a-1-dns/` | To do |
| 3a-2 | SSL with Let's Encrypt | `3a-2-ssl-lets-encrypt/` | To do |
| 3b-1 | Server automation scripts | `3b-1-automation/` | To do |
| 4 | Additional service: MariaDB | `4-mariadb/` | To do |

## Repository structure

- One folder per lab, each with a `notes.md` (commands, problems, fixes) and a `screenshots/` folder
- `scripts/` holds the Bash scripts and cron entries

## Security note

No private keys, passwords or certificates are stored here. See `.gitignore`.
