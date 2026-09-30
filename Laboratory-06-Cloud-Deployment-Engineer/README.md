# Laboratory 06: The Cloud Deployment Engineer

## Mission Overview
As a Cloud Deployment Engineer for CloudNova Technologies, this mission involved deploying a proof-of-concept private cloud storage platform using Nextcloud and MariaDB. Moving beyond single-container setups, this activity introduced Infrastructure as Code (IaC) principles by using Docker Compose to orchestrate a two-tier architecture smoothly[cite: 1].

## Objectives
- Explain multi-tier application architecture and component isolation[cite: 1].
- Write and structure a multi-container docker-compose.yml file[cite: 1].
- Use terminal text editors (nano) to construct configuration files[cite: 1].
- Deploy, verify, and tear down a two-tier stack using Docker Compose commands[cite: 1].
- Document deployment processes and IaC principles[cite: 1].

## Commands Executed
```bash
mkdir nextcloud-deployment && cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down

## Skills Learned
- Infrastructure as Code (IaC): Defining multi-container environments in declarative YAML configuration files[cite: 1].
- Multi-Tier Orchestration: Linking application containers to database services over an isolated Docker network[cite: 1].
- Lifecycle Management: Spinning up complete application environments and performing clean stack teardowns with minimal effort[cite: 1].
