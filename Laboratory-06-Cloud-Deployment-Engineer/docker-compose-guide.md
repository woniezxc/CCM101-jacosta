# Docker Compose & Infrastructure as Code Guide

## Overview
Infrastructure as Code (IaC) allows developers to define containerized environments using configuration files rather than manually typing long terminal commands[cite: 1]. This document explains the key components of the `docker-compose.yml` file used to launch the Nextcloud and MariaDB stack[cite: 1].

---

## The Configuration Code (`docker-compose.yml`)

```yaml
version: '3'

services:
  database:
    image: mariadb:10.6
    environment:
      - MYSQL_ROOT_PASSWORD=cloudnova_root
      - MYSQL_PASSWORD=cloudnova_pass
      - MYSQL_DATABASE=nextcloud_db
      - MYSQL_USER=nextcloud_user

  app:
    image: nextcloud
    ports:
      - 8080:80
    environment:
      - MYSQL_PASSWORD=cloudnova_pass
      - MYSQL_DATABASE=nextcloud_db
      - MYSQL_USER=nextcloud_user
      - MYSQL_HOST=database
