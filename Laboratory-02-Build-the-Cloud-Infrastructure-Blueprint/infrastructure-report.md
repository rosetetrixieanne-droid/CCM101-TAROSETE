# Infrastructure Report

## Checkpoint 2 - Investigate the Cloud Server

## Operating System

### Command used: 

cat /etc/os-release

Operating System: Ubuntu 24.04.4 LTS
Version Codename: Noble Numbat
Version ID: 24.04

## Kernel Version

### Command used: 

uname -r

Kernel Version: 6.8.0-138-generic

## CPU Model

### Command used:

lscpu | grep "Model name" 

CPU Model: Intel Xeoon E312xx (Sandy Bridge, IBRS update)

## Number of CPU Cores

### Command used: 

nproc

Number of CPU Cores/Available CPUs: 1

## Total RAM

### Command used:

free -h

Total RAM: 1.9 GiB
Available RAM: 1.5 GiB
Swap: 1.0 GiB

## Disk Capacity

### Command used:

df -h / 

Main Disk: /dev/vda1
Capacity: 19 GiB
Used: 5.4 GiB
Available: 13 GiB
Usage: 30%
Mounted on: /

## Mounted File System

### Command used:

df -h

File System | Size | Used | Available | Use | Mounted On |
tmpfs | 191M | 996K | 190M | 1% | /run | 
/dev/vda1 | 19G | 5.4G | 13G | 30% | / |
tmpfs | 952M | 84K | 952M | 1% | /dev/shm |
/dev/vda16 | 881M | 117M | 703M | 15% | /boot | 
/dev/vda15 | 105M | 6.2M | 99M | 6% | /boot/efi | 

## Hostname 

### Command used: 

hostname 

Hostname: ubuntu

## IP Address

### Command used: 

hostname -I 

IP Addresses: 172.30.1.2 and 172.17.0.1
