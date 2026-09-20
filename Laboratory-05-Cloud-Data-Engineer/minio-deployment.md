# MinIO Object Storage Deployment

## Docker Deployment Command

The MinIO server was deployed using Docker with ports 9000 and 9001 exposed.

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server -e "MINIO_ROOT_USER=cloudadmin" -e "MINIO_ROOT_PASSWORD=CloudNova2026!" quay.io/minio/minio server /data --console-address ":9001"
```

## Port Used

The MinIO Web Console was accessed through port **9001**.

Port **9000** was used for the MinIO API, while port **9001** was used for the web-based management console.

## Bucket Created

The bucket created for the proof-of-concept storage environment was:

```text
client-photos
```

A sample file was uploaded to the bucket to verify that the object storage system was working properly.

## Environment Variables

The `-e` flags were used to define environment variables for the MinIO container.

```text
MINIO_ROOT_USER=cloudadmin
```

This sets the administrator username used to log in to the MinIO Console.

```text
MINIO_ROOT_PASSWORD=CloudNova2026!
```

This sets the administrator password used for authentication.

Using environment variables allows the required MinIO login credentials to be provided when the container is started.
