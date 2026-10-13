# Docker Deployment

## Pull the Nginx Image

```bash
docker pull nginx
```

This downloads the official Nginx image from Docker Hub to the local Docker environment.

## Run the Nginx Container

```bash
docker run -d --name my-nginx -p 8080:80 nginx
```

This creates and starts an Nginx container in detached mode and maps host port 8080 to container port 80.

## Check the Running Container

```bash
docker ps
```

This displays the containers that are currently running.

## Test the Web Server

```bash
curl http://localhost:8080
```

This sends an HTTP request to the Nginx web server and confirms that it is responding.

## Stop the Container

```bash
docker stop my-nginx
```

This stops the running Nginx container without deleting it.

## Verify the Container

```bash
docker ps
```

This checks the currently running containers and confirms that `my-nginx` has stopped.

## View Stopped Containers

```bash
docker ps -a
```

This displays both running and stopped containers.

## Remove the Container

```bash
docker rm my-nginx
```

This permanently removes the stopped `my-nginx` container from Docker.

## Lifecycle Summary

The container was first listed while running, then stopped, verified as stopped, and finally removed. These commands demonstrate the basic lifecycle of a Docker container.
