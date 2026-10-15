# Laboratory 8: The Cloud Security Engineer

## Mission Overview
As part of the Cloud Security Team at CloudNova Technologies[cite: 1], this laboratory focuses on implementing the principle of defense in depth by securing a live Ubuntu server using a host-based firewall (UFW) on the KillerCoda Playground[cite: 1].

## Objectives
* Understand the Attack Surface and the Principle of Least Privilege (PoLP).
* Perform basic security audits of active network ports on Linux servers[cite: 2].
* Configure UFW with a strict Default Deny policy[cite: 2].
* Implement granular port management for SSH and application traffic[cite: 2].
* Document security configurations and reflections in Markdown[cite: 2].

## Commands Executed
* `sudo ufw allow ssh`
* `sudo ufw default deny incoming`
* `sudo ufw default allow outgoing`
* `sudo ufw enable`
* `sudo docker run --name secure-web-app -p 8080:80 -d nginx`
* `sudo ufw allow 8080/tcp`
* `sudo ufw status verbose`

## Skills Learned
* Linux Host-Based Firewall Configuration (UFW)
* Network Port Auditing & Defense in Depth
* Threat Mitigation via Default Deny Policies
* Technical Markdown Documentation & Version Control
