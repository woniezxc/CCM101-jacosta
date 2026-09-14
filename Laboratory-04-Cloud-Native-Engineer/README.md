# Laboratory 4: Mission 4 - The Cloud-Native Engineer

## Mission Overview
This laboratory explores containerization concepts by setting up a Docker environment, deploying an Nginx web server, managing container lifecycles, and documenting technical workflows.

## Objectives
* Contrast Virtual Machines with Docker Containers.
* Verify Docker execution within a Linux cloud playground.
* Execute foundational Docker CLI commands.
* Deploy an Nginx container with port forwarding.
* Document technical operations using Markdown.

## Docker Commands Executed
* `docker --version` - Displays installed Docker version.
* `docker info` - Displays Docker engine system information.
* `docker pull nginx` - Pulls the Nginx image from Docker Hub.
* `docker run -d -p 8080:80 --name my-nginx nginx` - Runs Nginx in detached mode with port mapping.
* `curl http://localhost:8080` - Sends HTTP request to test web server.
* `docker ps` - Lists active containers.
* `docker stop my-nginx` - Stops the Nginx container.
* `docker ps -a` - Lists all containers (active and inactive).
* `docker rm my-nginx` - Deletes the Nginx container.

## Skills Learned
* Working with Docker CLI for container management.
* Mapping host network ports to container ports.
* Technical writing and repository structuring.

## Challenges Encountered
* Understanding port binding parameters (`-p host_port:container_port`).
* Remembering to stop a container before trying to remove it.
