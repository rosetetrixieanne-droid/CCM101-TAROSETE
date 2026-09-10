# Docker Deployment

## Docker Commands Executed

### 1. Pull the Nginx Image

```bash
docker pull nginx
```

This command downloads the official Nginx image from Docker Hub.

### 2. Run the Nginx Container

```bash
docker run -d --name nginx-server -p 8080:80 nginx
```

This command creates and starts an Nginx container in detached mode. It also connects port `8080` on the host machine to port `80` inside the container.

### 3. List Running Containers

```bash
docker ps
```

This command shows the Docker containers that are currently running.

### 4. Test the Nginx Web Server

```bash
curl http://localhost:8080
```

This command sends an HTTP request to the Nginx web server running on the local machine. It should display the HTML response from Nginx.

### 5. Stop the Container

```bash
docker stop nginx-server
```

This command stops the running Nginx container.

### 6. Verify the Container Status

```bash
docker ps -a
```

This command displays all Docker containers, including containers that have already been stopped. It can be used to verify the current status of the Nginx container.

### 7. Remove the Container

```bash
docker rm nginx-server
```

This command removes the stopped Nginx container from the system.

---

## Container Lifecycle

The container lifecycle demonstrated in this activity was:

**Pull Image → Run Container → Check Container → Stop Container → Verify Status → Remove Container**

The activity demonstrated the basic process of downloading a Docker image, creating a container, checking its status, stopping it, and finally removing it.

---

## Screenshot – Container Lifecycle

The screenshot below shows the Docker commands used to manage the Nginx container:

```text
docker ps
docker stop nginx-server
docker ps -a
docker rm nginx-server
docker ps -a
```

<img width="1267" height="328" alt="container-lifecycle" src="https://github.com/user-attachments/assets/19382340-2f16-4632-a7d5-b078930340ba" />
