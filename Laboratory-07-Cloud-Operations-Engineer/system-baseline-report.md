# System Baseline Report

## Host System Baseline

Before deploying the client website, I checked the resources of the Ubuntu host server to determine its current health and capacity.

### RAM

The total RAM available on the server is:

Command used:

```bash
free -h
```
### Root File System Storage

The total storage capacity of the root / file system is:

Command used:

```bash
df -h /
```

### CPU and Running Processes

I used the following command to observe the active processes and CPU load:

```bash 
top
```

The top command provides real-time information about CPU utilization, memory usage, running processes, and system load.

Why Disk Space Is Important

Checking disk space before a massive traffic surge is important because insufficient storage can prevent applications from writing logs, temporary files, and other data, which may cause services to fail.
