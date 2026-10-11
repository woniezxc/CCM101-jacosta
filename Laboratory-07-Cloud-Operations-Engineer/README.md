# Laboratory 7: The Cloud Operations Engineer

## Mission Overview
Stepped into the role of a Cloud Operations Engineer (SRE) at CloudNova Technologies to establish a server performance baseline, deploy a containerized Nginx web server, generate test traffic, and capture system metrics and logs to prove infrastructure readiness[cite: 1, 3].

## Objectives
* Utilize native Linux command-line tools to monitor host CPU, RAM, and Disk capacity[cite: 1].
* Deploy a web container and track real-time performance using Docker metrics[cite: 1].
* Generate web traffic and extract application access logs for analysis[cite: 1].
* Translate raw performance data into a readable technical report using Markdown[cite: 1].
* Continue expanding the professional GitHub Cloud Computing Portfolio[cite: 1].

## Monitoring Commands Executed
* `free -h` - Checked available system RAM[cite: 2].
* `df -h` - Verified available root storage capacity[cite: 2].
* `top` - Inspected active processes and CPU load[cite: 2].
* `docker run -d --name client-website -p 8080:80 nginx` - Deployed the client Nginx container[cite: 3].
* `curl http://localhost:8080` - Simulated web traffic requests[cite: 3].
* `docker logs client-website` - Extracted application access logs[cite: 3].
* `docker stats` - Streamed real-time container resource utilization[cite: 3].

## Skills Learned
* Establishing host system performance baselines on Linux.
* Deploying and managing containerized services via Docker[cite: 1].
* Analyzing access logs and HTTP status codes (`200 OK`, `404 Not Found`)[cite: 3].
* Monitoring live container resource consumption[cite: 3].
