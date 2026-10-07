# Laboratory 07 - Cloud Operations Engineer

## Mission Overview

CloudNova Technologies is preparing for a massive marketing campaign that may generate thousands of simultaneous users. This laboratory focuses on checking the health of the cloud host, deploying a containerized Nginx web server, generating test traffic, analyzing application logs, and monitoring container resource usage.

## Objectives

- Establish a baseline of the host server's RAM and disk storage.
- Monitor CPU and running processes using Linux tools.
- Deploy an Nginx web server using Docker.
- Generate successful HTTP requests and an intentional 404 error.
- Retrieve and analyze container application logs.
- Monitor real-time container CPU and memory usage.
- Document system health and observability results using Markdown.
- Maintain evidence through screenshots and GitHub commits.

## Monitoring Commands Executed

### RAM Monitoring

```bash
free -h
```

### Disk Monitoring
```bash
df -h /
```

### Process and CPU Monitoring
```bash
top
```

### Container Deployment
```bash
docker run -d -p 8080:80 --name client-website nginx
```

### Container Status
```bash
docker ps
```

### HTTP Testing
```bash
curl http://localhost:8080
```

### HTTP Error Testing
```bash
curl http://localhost:8080/hidden-admin-page
```

### Application Logs
```bash
docker logs client-website
```

### Container Metrics
```bash
docker stats
```

## Skills Learned

Through this laboratory, I learned how to establish a basic Linux server health baseline using standard command-line tools. I also learned how to deploy and test an Nginx Docker container, generate HTTP traffic, intentionally produce an HTTP 404 error, and inspect application logs.

I also practiced container observability by using docker stats to monitor CPU and memory consumption in real time. These skills are important for Cloud Operations Engineers because they help identify resource problems and application issues before they affect users.

## Evidences

Screenshots are stored in the screenshots folder:

memory-check.png
disk-check.png
top.png
install-nginx.png
simulation1.png
simulation2.png
docker-logs.png
container-metrics.png
