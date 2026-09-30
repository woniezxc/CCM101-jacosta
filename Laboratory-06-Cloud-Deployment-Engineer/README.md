### File 3: `README.md`

```markdown
# Laboratory 06: The Cloud Deployment Engineer

## Mission Overview
As a Cloud Deployment Engineer for CloudNova Technologies, this mission involved deploying a proof-of-concept private cloud storage platform using Nextcloud and MariaDB[cite: 1]. Moving beyond single-container setups, this activity introduced Infrastructure as Code (IaC) principles by using Docker Compose to orchestrate a two-tier architecture smoothly[cite: 1].

---

## Objectives
* Explain multi-tier application architecture and component isolation[cite: 1].
* Write and structure a multi-container `docker-compose.yml` file[cite: 1].
* Use terminal text editors (`nano`) to construct configuration files[cite: 1].
* Deploy, verify, and tear down a two-tier stack using Docker Compose commands[cite: 1].
* Document deployment processes and IaC principles[cite: 1].

---

## Commands Executed

```bash
# Create project folder and navigate inside
mkdir nextcloud-deployment && cd nextcloud-deployment

# Open nano editor to write compose configuration
nano docker-compose.yml

# Deploy the multi-container stack in detached mode
docker-compose up -d

# Verify container status
docker-compose ps

# Gracefully stop and remove all services
docker-compose down
