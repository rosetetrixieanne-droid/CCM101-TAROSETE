# CCM101 Cloud Computing

## Laboratory Activity 1 = Mission 1: Introduction to the Cloud

### Overview

This laboratory activity introduces the fundamental skills needed when working with cloud infrastructure. It focuses on using a Linux environment, navigating and managing 
files and directories, checking system information, and creating a GitHub portfolio to document technical work.

---

## Objectives

By completing this checkpoint, I was able to:
- Access an Ubuntu Linux environment using KillerCoda.
- Explore and verify the Linux terminal.
- Create a new Linux user account.
- Configure the user with:
  - Bash shell
  - Home directory
  - `sudo` privileges
- Log in to the newly created user account.
- Identify the current username, working directory, and hostname.

---

# Checkpoint 1 – Enter the Cloud


This activity I introduces the basic Linux environment used in cloud computing. The task involves accessing an Ubuntu Linux playground through KillerCoda, I created a Linux user account named tarosete, 
configured its Bash shell and home directory, and gave the account sudo privileges. And then used Linux commands to check the current, username, working directory, and hostname.

---

### User Information

| *Information* | *Result* | 
|---|---|
| Username | tarosete |
| Working Directory | /home/tarosete | 
| Hostname | [Your Hostname] |

## Mission Tasks

### 1. Access the Linux Playground

I accessed the Linux Playground through **KillerCoda** and selected **Ubuntu 24.04** or the latest available Ubuntu version.

**KillerCoda Playground:**  
https://killercoda.com/playgrounds

---

### 2. Command Used

After launching the playground, I explored the Linux environment and checked whether the terminal was working properly.

The following commands were used:

```bash
sudo adduser tarosete
sudo usermod -aG sudo tarosete
su - tarosete

whoami
pwd
hostname
