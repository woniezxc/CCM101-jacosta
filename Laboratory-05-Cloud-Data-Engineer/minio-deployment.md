# MinIO Deployment Documentation

## Deployment Command
The MinIO object storage server was containerized and launched using Docker with the following command:

```text
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
  -e "MINIO_ROOT_USER=cloudadmin" \
  -e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
  minio/minio server /data --console-address ":9001"
