# Laboratory 08: Cloud Security Engineer

## Mission Overview

This mission focuses on securing an Ubuntu server
using the UFW host-based firewall and protecting
a web application running through Nginx.

## Objectives

- Understand the Principle of Least Privilege.
- Identify the server's attack surface.
- Configure a Default Deny firewall policy.
- Allow SSH and TCP port 8080.
- Document security configurations.

## Commands Executed

- `docker --version`
- `docker ps`
- `curl http://localhost:8080`
- `sudo ufw allow ssh`
- `sudo ufw default deny incoming`
- `sudo ufw default allow outgoing`
- `sudo ufw enable`
- `sudo ufw status verbose`
- `sudo ufw allow 8080/tcp`
- `sudo ufw status numbered`

## Skills Learned

- Linux server administration
- Docker container deployment
- Firewall configuration
- Network port management
- Technical documentation using Markdown
- GitHub portfolio management
