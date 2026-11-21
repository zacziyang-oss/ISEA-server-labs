# ISEA Server Labs

Lab documentation for BRG27-ISEA: Introduction to Server Environments and Architectures.

## About

This is about the labs i have completed over the past 3 weeks and what i had to do differently to fix issues that come up


## Environment

- Host machine: MACBOOK AIR (M2)
- Virtualisation: UTM
- Guest OS: Ubuntu 26.04 ARM64
- Cloud platform: AWS EC2, Ubuntu

## Labs

| Lab | Topic | Folder |
| --- | --- | --- |
| 1a-1 | Obtaining a Linux environment | [1a-1-obtaining-linux](1a-1-obtaining-linux/)
| 1a-2 | Ubuntu familiarisation | [1a-2-ubuntu-familiarisation](1a-2-ubuntu-familiarisation/) 
| 1b-1 | Linux services | [1b-1-linux-services](1b-1-linux-services/)
| 1b-2 | Linux permissions | [1b-2-linux-permissions](1b-2-linux-permissions/)
| 1b-3 | File system search | [1b-3-file-system-search](1b-3-file-system-search/)
| 2a-1 | TCO comparison | [2a-1-tco-comparison](2a-1-tco-comparison)
| 2b-1 | AWS EC2 deployment | [2b-1-aws-ec2](2b-1-aws-ec2/)
| 2b-2 | Bash scripting and regex | [2b-2-bash-scripting](2b-2-bash-scripting/)
| 3a-1 | DNS configuration | [3a-1-dns](3a-1-dns/)
| 3a-2 | SSL with Let's Encrypt | [3a-2-ssl-lets-encrypt](3a-2-ssl-lets-encrypt/)
| 3b-1 | Bash scripting, cron jobs & cloud export | [3b-1-automation](3b-1-automation/)
| 4 | Additional service: MariaDB | [4-mariadb](4-mariadb/)

## Repository structure

- One folder per lab, each with a `notes.md` (commands, problems, fixes) and a `screenshots/` folder
- `scripts/` holds the Bash scripts and cron entries

## Security note

No private keys, passwords or certificates are stored here. See `.gitignore`.
