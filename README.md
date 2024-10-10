# DevOps with Docker course work, Exercise 3.1
<https://devopswithdocker.com/part-3/section-2>


## express app

This repository has a Github Action to build and deploy a Docker image to DockerHub.

Docker compose file sets up a Watchtower container to watch the Docker image in Docker Hub. When a new version of the image is available, Watchtower will pull the new image and restart the container.



To run the app with Watchtower, run the following commands:

```bash
docker compose -f compose-watchtower.yml up
```


Access with browser http://localhost:8080
