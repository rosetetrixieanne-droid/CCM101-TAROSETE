# Container Observability

## Application Logs

The application logs were retrieved using:

```bash
docker logs client-website
```

## HTTP 404 Error

```text
172.17.0.1 - - [07/Oct/2026:01:39:03 +0000] "GET /hidden-admin-page HTTP/1.1" 404 153 "-" "curl/8.5.0" "-"
```

Application logs are vital for troubleshooting because they show what requests are being made and whether they succeed or fail. They help developers identify errors such as missing pages, incorrect configurations, and other problems so they can quickly determine what needs to be fixed.

## Real-Time Container Metrics

The Docker container was monitored using:

```bash
docker stats
```

## Client Website Metrics

At the time of the screenshot, the client-website container showed:

CPU Usage: [ACTUAL CPU %]
Memory Usage: [ACTUAL MEMORY USAGE]
Network I/O: [OPTIONAL - ACTUAL VALUE]

The CPU percentage indicates how much CPU processing the container was using, while memory usage shows the amount of RAM consumed by the container.
