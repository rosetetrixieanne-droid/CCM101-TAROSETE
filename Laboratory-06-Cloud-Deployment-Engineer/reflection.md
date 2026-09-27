# Mission Reflection

This laboratory helped me understand how Docker Compose can make cloud deployment easier and more organized. Instead of manually typing many Docker commands for every container, I can place the configuration in a `docker-compose.yml` file and use one command to start the whole application. This is useful because the same configuration can be reused when the system needs to be deployed again. It also makes the setup easier for another engineer to understand.

I also learned that YAML is very sensitive to indentation. Spaces are important because they show the relationship between different parts of the configuration. If I use a Tab instead of spaces or put something at the wrong indentation level, Docker Compose may not understand the file and can return an error. This made me realize that small formatting mistakes can affect an entire deployment.

We used environment variables such as `MYSQL_PASSWORD`, `MYSQL_DATABASE`, and `MYSQL_USER` because they provide configuration values that the containers need while starting. They also make the configuration easier to change without modifying the application itself. I learned that environment variables are commonly used when connecting different services in a containerized environment.

It was interesting to see Nextcloud running after only a few deployment commands. Seeing the setup page in the browser made the concept of cloud deployment feel more practical to me because I was able to build an actual private cloud storage environment.

Since Mission 1, my understanding of Cloud Computing has improved. I started with basic Linux commands and cloud concepts, and now I understand more about containers, services, networking, databases, and multi-tier deployments. This laboratory showed me how different technologies can work together to create a complete cloud-based system.
