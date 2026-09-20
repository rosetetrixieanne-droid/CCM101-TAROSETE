# Mission Reflection

This laboratory helped me understand why object storage is useful for applications that handle a large amount of files such as photos. Object storage is better suited for millions of photos because it is designed for storing unstructured data and can scale as the amount of data increases. Unlike a traditional block storage hard drive, object storage organizes files as objects with their own data and metadata. This makes it useful for applications that need to store and retrieve many images.

Using Docker also made the deployment of MinIO easier. Instead of manually installing and configuring all the required software, I was able to start MinIO using a Docker command. The command also allowed me to configure the ports and administrator credentials when the container was created. Docker made the process more organized because MinIO ran inside its own container.

A bucket in cloud storage is a logical container where objects or files are stored. In this activity, I created a bucket named `client-photos` and uploaded a sample file to it. The bucket can be used to organize the images uploaded by users of the photo-sharing application.

Large enterprise companies can use different methods to help protect their object storage data from being lost when a physical server crashes. They can keep multiple copies of data, use redundancy, perform regular backups, and distribute storage across different servers or locations. These methods can help make the data available even when one physical machine experiences a problem.

My confidence in using the Linux command line is also improving. At first, commands can feel confusing because most tasks are done through text. However, after using commands such as `cd`, `ls`, `nano`, `docker run`, and `docker ps`, I became more comfortable working in the terminal. This activity helped me understand that the Linux command line is an important skill when working with cloud and container technologies.
