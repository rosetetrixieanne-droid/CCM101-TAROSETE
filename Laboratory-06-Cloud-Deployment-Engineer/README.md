# Laboratory 06 – Cloud Deployment Engineer

## Mission Overview

This laboratory focuses on deploying a private cloud storage environment using Nextcloud and Docker Compose. The project uses a two-tier architecture consisting of a Nextcloud application container and a MariaDB database container.

## Objectives

* Understand two-tier architecture.
* Create a Docker Compose configuration.
* Deploy multiple containers as one application stack.
* Connect a Nextcloud application to a MariaDB database.
* Access the Nextcloud web interface.
* Practice starting and stopping a multi-container environment.
* Document the deployment process using Markdown.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

Additional Git commands were used to save the laboratory documentation to the existing GitHub portfolio repository.

## Skills Learned

Through this laboratory, I learned how Docker Compose can be used to deploy multiple related containers. I also learned how environment variables allow the Nextcloud application to connect to the MariaDB database. The activity improved my understanding of multi-tier architecture, container networking, YAML configuration, and basic cloud deployment practices.
