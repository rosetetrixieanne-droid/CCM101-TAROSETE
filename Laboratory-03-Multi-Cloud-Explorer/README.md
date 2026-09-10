# Mission 3 – Multi-Cloud Explorer

## Checkpoint 7 – Exploring a Linux Environment with KillerCoda

For this checkpoint, a Linux environment was explored using KillerCoda. Different Linux commands were used to collect basic information about the system, including the operating system, CPU, memory, and disk storage.

---

## 1. Identifying the Operating System

The operating system and its version were checked using the following command:

```bash
cat /etc/os-release
```

This command displays information about the Linux distribution installed in the environment. It shows details such as the operating system name, version, and other system identification information.

### Terminal Evidence 1 – Operating System Information

<img width="970" height="369" alt="killercoda-terminal1" src="https://github.com/user-attachments/assets/c01cfce3-20ac-42ae-8458-da1b94ef8619" />

---

## 2. Checking the CPU Information

The CPU specifications were checked using:

```bash
lscpu
```

This command displays different details about the processor, including the CPU architecture, number of CPUs, and other information about the system's processor.

### Terminal Evidence 2 – CPU Information

<img width="1336" height="820" alt="killercoda-terminal2" src="https://github.com/user-attachments/assets/105f41b3-8bdc-4046-afdb-b487b10562fd" />


---

## 3. Checking the Memory

The system memory was checked using:

```bash
free -h
```

The `-h` option makes the memory values easier to read. The command displays information about the total memory, used memory, free memory, and available memory.

### Terminal Evidence 3 – Memory Information

<img width="748" height="94" alt="killercoda-terminal3" src="https://github.com/user-attachments/assets/eede2d5c-3ea9-477f-85ca-8f675b4b8ee9" />


---

## 4. Checking the Disk Space

The available disk space was checked using:

```bash
df -h
```

This command shows information about the file systems and their storage capacity. It includes the total space, used space, available space, and percentage of storage being used.

### Terminal Evidence 4 – Disk Space Information

<img width="528" height="173" alt="killercoda-terminal4" src="https://github.com/user-attachments/assets/b6f2ec9c-5ecb-44f7-a413-37c496534ec4" />


---

## System Investigation Summary

| Information Checked | Linux Command         | Evidence            |
| ------------------- | --------------------- | ------------------- |
| Operating System    | `cat /etc/os-release` | Terminal Evidence 1 |
| CPU                 | `lscpu`               | Terminal Evidence 2 |
| Memory              | `free -h`             | Terminal Evidence 3 |
| Disk Space          | `df -h`               | Terminal Evidence 4 |

These Linux commands are useful for quickly checking the basic hardware and system resources of a Linux machine. They can also help system administrators understand the current condition and available resources of a server.

---

## Possible Cloud Migration

A Linux server running on a local computer or virtual environment can also be moved to a cloud platform. AWS, Microsoft Azure, and Google Cloud all provide virtual machine services that can support Linux operating systems.

| Cloud Platform            | Virtual Machine Service |
| ------------------------- | ----------------------- |
| Amazon Web Services (AWS) | Amazon EC2              |
| Microsoft Azure           | Azure Virtual Machines  |
| Google Cloud              | Compute Engine          |

These cloud services allow organizations to run Linux servers using cloud-based virtual machines. Instead of managing physical server hardware, the organization can use the infrastructure provided by the cloud provider.

