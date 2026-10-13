# Mission 4 Reflection

This laboratory activity helped me understand why containerization is commonly used in modern cloud computing. A Docker container can start much faster than a Virtual Machine because it does not need to boot a complete operating system. With a VM, the operating system has to be installed and started before the application can be used. In Docker, an existing image can be pulled and used to create a container in a much shorter time. This makes containers useful when applications need to be deployed quickly.

The port mapping `-p 8080:80` is necessary because the Nginx web server is running inside the container on port 80. The mapping connects port 8080 on the host to port 80 inside the container. This allows me to access the Nginx server using `http://localhost:8080` from the host environment. Without the correct port mapping, the web server may not be accessible through the host's port.

When `docker rm` is used, the container itself is removed. Any data stored only inside the container can be lost after the container is removed. This is why persistent data should normally be stored using Docker volumes or another external storage solution instead of depending only on the container.

Containerization can also improve the way developers and IT operations teams work together. Developers can package an application and its dependencies into a container, while operations teams can deploy the same container in different environments. This supports the DevOps approach because development, testing, and deployment become more consistent.

My GitHub portfolio is also evolving as I add more laboratory activities and technical documentation. This activity adds Docker and containerization skills to my previous cloud computing work. It also gives me practical evidence that I can use basic Docker commands and document a cloud-native deployment.
