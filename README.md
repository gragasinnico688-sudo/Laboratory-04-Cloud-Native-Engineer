# Laboratory 04 — Cloud-Native Engineer

## Mission Overview

This laboratory activity introduces containerization and Docker. The activity compares Virtual Machines and containers and demonstrates how Docker can be used to deploy an Nginx web server quickly. The commands were performed using the KillerCoda Playground.

## Objectives

- Differentiate Virtual Machines and containers.
- Access a Docker-enabled Linux environment.
- Use basic Docker CLI commands.
- Pull and run an Nginx container.
- Manage the lifecycle of a Docker container.
- Document Docker operations using Markdown.

## Docker Commands Executed

### Check Docker

```bash
docker --version
docker info
docker ps
```

### Deploy Nginx

```bash
docker pull nginx
docker run -d --name my-nginx -p 8080:80 nginx
docker ps
curl http://localhost:8080
```

### Manage the Container

```bash
docker stop my-nginx
docker ps
docker ps -a
docker rm my-nginx
docker ps -a
```

## Skills Learned

Through this activity, I learned how containers differ from virtual machines and how Docker manages containerized applications. I also learned how to pull images, run containers, check their status, stop them, and remove them. I gained experience using Docker commands in a Linux environment and documenting technical procedures using Markdown.

## Challenges Encountered

One challenge was understanding the difference between a Docker image and a container. I also had to understand how port mapping works when accessing a web server inside a container. Running the commands one by one helped me understand the container lifecycle and how Docker manages applications.
