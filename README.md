# Docker Practice
Build and run a Docker image using Dockerfile or Docker compose.

## Target: Dockerizing a Node.js web app
1. Use Dockerfile to build a Docker image
2. Usd Docker CLI to run the image.
3. Use Docker CLI to manage your conatiner.
### Common Docker CLI
```
docker build -t <image_name> .
docker run -p 49160:8080 -d node-web-app
docker ps
docker ps -a
docker images
docker start <container_name>
docker stop <constainer_name>
docker rm <container_name>
docker rmi <image_name>
docker logs <container_name>
docker exec -it <container_name> /bin/bash
```

4. Use Docker compse to run a Docker image.

reference:https://nodejs.org/de/docs/guides/nodejs-docker-webapp/
