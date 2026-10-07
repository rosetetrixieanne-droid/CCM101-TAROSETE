
# Mission Reflection

This laboratory helped me understand why monitoring both the host server and containers is important in cloud operations. Even if the containers are running perfectly, the host server can still experience problems such as high memory usage, insufficient disk space, or high CPU utilization. If the host resources become exhausted, the containers may become slow or stop working. Checking RAM, disk storage, CPU load, and running processes gives the Cloud Operations Engineer a baseline that can be used to identify unusual changes during high traffic.

The `docker logs` command is also useful when troubleshooting problems reported by users. For example, if a user cannot log into a web application, I can use `docker logs` to check the events and requests recorded by the application container. The logs may show HTTP errors, failed requests, connection problems, or other information that can help identify the cause of the problem. Instead of guessing, the engineer can use the recorded events as evidence.

There is a difference between monitoring logs and monitoring metrics. Logs provide detailed records of events and application activities, while metrics provide numerical information about system performance. In this laboratory, the logs showed the successful HTTP requests and the 404 error, while `docker stats` showed the CPU and memory usage of the container.

Large enterprise companies cannot manually monitor thousands of containers one by one. They can use monitoring and observability platforms such as Prometheus and Grafana to collect, organize, visualize, and alert engineers about system performance. These tools make it easier to identify problems across many servers and containers.

My ability to troubleshoot Linux environments improved because I became more comfortable using commands such as `free`, `df`, `top`, `curl`, `docker logs`, and `docker stats`. I also learned how to use actual system outputs as evidence when diagnosing infrastructure problems.
