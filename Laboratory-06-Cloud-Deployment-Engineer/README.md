### File 3: `README.md`

```markdown
# Laboratory 06: The Cloud Deployment Engineer

## Mission Overview
As a Cloud Deployment Engineer for CloudNova Technologies, this mission involved deploying a proof-of-concept private cloud storage platform using Nextcloud and MariaDB. Moving beyond single-container setups, this activity introduced Infrastructure as Code (IaC) principles by using Docker Compose to orchestrate a two-tier architecture smoothly.

---

## Objectives
* Explain multi-tier application architecture and component isolation.
* Write and structure a multi-container `docker-compose.yml` file.
* Use terminal text editors (`nano`) to construct configuration files.
* Deploy, verify, and tear down a two-tier stack using Docker Compose commands.
* Document deployment processes and IaC principles.

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
