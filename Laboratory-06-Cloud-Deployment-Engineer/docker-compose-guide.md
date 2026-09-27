# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block defines the containers or services that Docker Compose will create and manage. In this project, there are two services: `database` for MariaDB and `app` for the Nextcloud application. Docker Compose uses these definitions to create the required containers and configure how they work together.

## How Does Nextcloud Find the Database?

The Nextcloud container uses the `MYSQL_HOST` environment variable to find the database container.

The Compose file contains:

```yaml
- MYSQL_HOST=database
```

The value `database` matches the name of the MariaDB service:

```yaml
database:
```

Docker Compose creates an internal network for the services, allowing the Nextcloud application to communicate with the database by using the service name `database`.

## `docker run` vs `docker-compose up -d`

The `docker run` command is normally used to create and start one container at a time. It requires the user to provide the image, ports, environment variables, volumes, and other options directly in the command.

On the other hand, `docker-compose up -d` reads the configuration from a Compose YAML file and can create and start multiple related containers at the same time. The `-d` option runs the containers in the background, allowing the terminal to be used for other commands.


