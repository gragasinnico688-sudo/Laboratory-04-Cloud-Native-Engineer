🚀 Laboratory 04: The Cloud-Native Engineer

!Docker !Platform !Documentation

📌 Mission Overview

This laboratory explores the differences between traditional Virtual Machines (VMs) and containers. Using the KillerCoda playground, I practiced fundamental Docker commands and deployed an Nginx web server inside a container.

🎯 Objectives
Understand the differences between virtual machines and containers.
Verify Docker installation and service availability.
Pull and run an Nginx container.
Configure port mapping to access a web server.
Manage the container lifecycle using Docker CLI commands.
Document technical procedures using Markdown.
Expand my GitHub Cloud Computing Portfolio.
🛠️ Tools and Technologies
Docker
Nginx
KillerCoda Playground
Ubuntu/Linux terminal
Git and GitHub
Markdown
🐳 Docker Commands Executed
1. Verify Docker
docker --version
docker info
systemctl status docker

2. Deploy Nginx
docker pull nginx
docker run -d --name nginx-server -p 8080:80 nginx
curl http://localhost:8080

3. Manage the Container
docker ps
docker stop nginx-server
docker ps
docker ps -a
docker rm nginx-server
docker ps -a

📸 Screenshots and Evidence
Docker Environment Verification

!Docker Version

Nginx Web Server Running

!Nginx Running

Container Lifecycle

!Container Lifecycle

📚 Laboratory Documentation
Virtual Machines vs. Containers
Docker Deployment Guide
Mission Reflection
💡 Skills Learned
Docker image management
Container deployment and port mapping
HTTP testing using curl
Container inspection, stopping, and removal
Technical documentation and GitHub version control
⚠️ Challenges Encountered

Document the actual problems you experienced during the laboratory, the commands you used to investigate them, and how you resolved them.

✅ Mission Success Criteria
Compared VMs and containers.
Verified Docker availability.
Successfully deployed Nginx.
Verified the web server using curl.
Stopped and removed the container.
Added all required screenshots.
Completed and pushed all documentation.

Course: Cloud Computing
Activity: Laboratory 04 – The Cloud-Native Engineer
Portfolio: Cloud Computing GitHub Repository
