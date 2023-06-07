## build docker
docker build -t one-api:1.0 .

## upload
docker tag one-api:1.0 faotbgs/oneapi:1.0
docker push faotbgs/oneapi:1.0