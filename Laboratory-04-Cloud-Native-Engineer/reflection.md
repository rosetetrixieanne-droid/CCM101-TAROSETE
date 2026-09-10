# Mission Reflection

This laboratory activity helped me understand how containers are used in
cloud-native environments. I learned that Docker containers can start much
faster than Virtual Machines because a container does not need to install
and boot a complete operating system. A Virtual Machine requires its own
guest operating system, which can use more RAM, storage, and processing
resources. In comparison, containers share the host operating system and
only contain the application and the files needed to run it. Because of
this, containers are useful for quickly deploying applications.

I also learned why port mapping such as `-p 8080:80` is necessary when
running a web server inside a container. The Nginx server runs on port 80
inside the container, but users access the service through the host port.
By mapping port 8080 to port 80, requests sent to `localhost:8080` can
reach the Nginx web server inside the container.

Another important lesson was what happens when the `docker rm` command is
used. The command removes the container itself after it has been stopped.
Any data stored only inside the container can be lost when the container is
removed unless persistent storage such as Docker volumes is used. This
showed me why proper data management is important when working with
containers.

Containerization also changes how developers and IT operations teams work
together. Developers can package an application with its required
dependencies, while operations teams can deploy the same container in
different environments. This supports the DevOps approach because it makes
deployment more consistent and easier to manage.

Finally, my GitHub portfolio is becoming more organized as I continue
adding new laboratory activities. Each laboratory contains documentation,
screenshots, technical commands, and reflections. This makes my repository
a useful record of the cloud computing skills I have learned throughout
the semester.
