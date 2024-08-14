# Ansible LAMP Test

This repository contains the Ansible scripts for installing a LAMP stack using Docker Compose.

For testing, I have set up a [AWS EC2 Virtual Machine](https://eu-central-1.console.aws.amazon.com/ec2/home?region=eu-central-1#InstanceDetails:instanceId=i-0200e46d3ff3f5aa6) running Alma Linux 9.4.2

## Usage

Run ansible scripts

```
$ ansible-playbook install-docker.yml
$ ansible-playbook run-lamp-docker.yml
```

SSH directly into EC2 server
```
ssh -i Alma\ Linux.pem ec2-user@3.76.124.180
```

## Learning resources

[Ansible Docs](https://docs.ansible.com/)

[Getting started with Ansible (Learn Linux TV)](https://www.youtube.com/playlist?list=PLT98CRl2KxKEUHie1m24-wkyHpEsa4Y70)

[Installing Docker on Alma Linux](https://www.liquidweb.com/blog/install-docker-on-linux-almalinux/)

[Installing a LAMP server with Docker Images](https://medium.com/@mikez_dg/how-to-set-up-a-simple-lamp-server-with-docker-images-in-2023-9b0e24476ec6)
