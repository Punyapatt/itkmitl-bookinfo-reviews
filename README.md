# itkmitl-bookinfo-reviews
* How to run with Docker
```bash
# Build Docker image for details service
docker build -t java .

# Run docker container
docker run -d --name reviews -p 8082:9080 java
```
