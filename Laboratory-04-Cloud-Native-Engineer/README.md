# Laboratory 04 – Cloud-Native Engineer

## Mission Overview

This laboratory activity introduced the basic concepts of cloud-native engineering and containerization. I learned the differences between Virtual Machines and Containers and used Docker to deploy an Nginx web server. The activity was completed using the KillerCoda Docker playground.

## Objectives

* Understand the differences between Virtual Machines and Containers.
* Verify that Docker is installed and running.
* Execute basic Docker CLI commands.
* Pull and run an Nginx container.
* Map a host port to a container port.
* Manage the lifecycle of a Docker container.
* Document Docker operations using Markdown.

## Docker Commands Executed

### Check Docker Installation

```bash
docker --version
```

### Check Docker Information

```bash
docker info
```

### Pull Nginx

```bash
docker pull nginx
```

### Run Nginx

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

### List Running Containers

```bash
docker ps
```

### Test Nginx

```bash
curl http://localhost:8080
```

### Stop Container

```bash
docker stop nginx-server
```

### View All Containers

```bash
docker ps -a
```

### Remove Container

```bash
docker rm nginx-server
```

## Skills Learned

* Docker CLI fundamentals
* Container deployment
* Nginx deployment
* Port mapping
* Container lifecycle management
* Linux terminal commands
* Technical documentation using Markdown
* GitHub repository organization

## Challenges Encountered

One challenge I encountered was understanding the difference between a Virtual Machine and a Docker container. I also needed to understand how port mapping works when accessing a web server inside a container. Running the Docker commands helped me understand the process better. Another challenge was checking the container status and making sure the Nginx container was properly stopped and removed.
