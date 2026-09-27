# Multi-Tier Architecture

## What is a Two-Tier Architecture?

A Two-Tier Architecture is a system design where the application is separated into two main parts: the web/application tier and the database tier. In this Nextcloud deployment, the two parts are placed in separate Docker containers so they can communicate with each other while having different responsibilities.

## The Web/Application Tier

The web/application tier is responsible for running the Nextcloud application. It handles HTTP requests from users and provides the web interface where users can access and manage their files. In this laboratory, the Nextcloud application runs inside the `app` container and uses port 8080 to provide access to the web interface.

## The Database Tier

The database tier is responsible for storing persistent information needed by Nextcloud. This includes user accounts, credentials, configuration information, and file metadata. In this deployment, MariaDB runs inside the `database` container and provides the database used by Nextcloud.

## Why Separate Them?

Separating the web application and database into different containers makes the system easier to manage and maintain. Each container has a specific responsibility, so the application and database can be updated, restarted, or managed independently. This also creates a cleaner architecture compared to placing both services inside one container.
