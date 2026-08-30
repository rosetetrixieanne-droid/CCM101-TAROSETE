# Cloud Infrastructure Components

##  Identify Cloud Infrastructure Components

## 1. Compute Resources

### Purpose

Compute resources provide the processing power needed to run commands, applications, and services. They mainly include the CPU and RAM of the server.

### Importance in Cloud Computing

Compute resources are important in cloud computing because applications and services need processing power and memory to operate. Cloud computing allows these resources to be provided virtually and adjusted depending on the workload.

### KillerCoda Linux Environment

The KillerCoda environment provides a virtual CPU and RAM for running Linux and performing cloud computing activities.

Based on the infrastructure investigation:

- **CPU:** Intel Xeon E312xx (Sandy Bridge, IBRS update)
- **Available CPU Cores:** 1
- **Total RAM:** 1.9 GiB
- **Available RAM:** 1.5 GiB
- **Swap:** 1.0 GiB

These resources allow the virtual Linux server to execute commands and run the required laboratory activities.

---

## 2. Storage Resources

### Purpose

Storage resources provide space for storing the operating system, applications, configuration files, and user data.

### Importance in Cloud Computing

Storage is important in cloud computing because servers and applications need a place to store data. Cloud storage can also be managed and expanded according to the needs of users and applications.

### KillerCoda Linux Environment

The KillerCoda Linux environment provides virtual disk storage for the operating system and other files.

Based on the infrastructure investigation:

- **Main Disk:** `/dev/vda1`
- **Capacity:** 19 GiB
- **Used:** 5.4 GiB
- **Available:** 13 GiB
- **Usage:** 30%
- **Mounted on:** `/`

The main disk stores the Ubuntu operating system, installed software, system files, and other data needed by the Linux environment.

The system also contains mounted filesystems such as `/boot`, `/boot/efi`, `/run`, and `/dev/shm`.

---

## 3. Networking Resources

### Purpose

Networking resources allow computers, servers, and applications to communicate with each other. These resources include network interfaces, IP addresses, and network connections.

### Importance in Cloud Computing

Networking is essential in cloud computing because users need to connect to cloud servers and applications remotely. It also allows different cloud services and systems to communicate with one another.

### KillerCoda Linux Environment

The KillerCoda Linux environment has a hostname and IP addresses that identify the virtual server within its network.

Based on the infrastructure investigation:

- **Hostname:** `ubuntu`
- **IP Address:** `172.30.1.2`
- **Additional IP Address:** `172.17.0.1`

The IP addresses allow the Linux environment to communicate over its virtual network. The hostname `ubuntu` provides an easy way to identify the server.

These networking resources demonstrate how a cloud-based Linux server can communicate within a virtualized cloud infrastructure.

---

## 4. Operating System

### Purpose

The operating system manages the computer's hardware and software resources. It provides the environment where users can execute commands, manage files, install software, and run applications and services.

### Importance in Cloud Computing

The operating system is an important part of cloud computing because cloud servers need an operating system to manage compute, storage, networking, users, and applications. Linux is commonly used in cloud environments because it is flexible, reliable, and efficient.

### KillerCoda Linux Environment

The operating system provided by KillerCoda is:

- **Operating System:** Ubuntu 24.04.4 LTS
- **Codename:** Noble Numbat
- **Version ID:** 24.04
- **Kernel:** 6.8.0-138-generic

Ubuntu provides the command-line environment and system tools used to investigate and manage the cloud server.

The Linux operating system works together with the available CPU, RAM, storage, and networking resources to provide a functional cloud server environment.
