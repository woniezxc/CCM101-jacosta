# Multi-Tier Application Architecture

## Overview
Modern cloud applications rely on structured architectures to separate duties, scale efficiently, and remain maintainable. This document breaks down the two-tier architecture model implemented for the Nextcloud and MariaDB deployment.

---

## 1. The Web / Application Tier
The **Web/Application Tier** serves as the public face of the platform. Its primary duties include:
* Handling incoming HTTP/HTTPS requests from clients.
* Rendering the Nextcloud web user interface.
* Executing core application logic, processing user actions, and orchestrating file uploads and downloads.

In this lab, the Nextcloud container acts as the application tier.

---

## 2. The Database Tier
The **Database Tier** handles backend data management and persistence. Its key responsibilities include:
* Storing metadata, user accounts, authentication tokens, file directory trees, and configuration flags.
* Managing structured queries requested by the application tier.
* Securing persistent system data independently of web traffic.

In this lab, the MariaDB container fulfills this role.

---

## 3. Why Separate the Tiers?
Combining a web server and a database into a single container creates security risks and operational bottlenecks. Decoupling them into separate containers provides distinct operational advantages:

1. **Scalability:** The web tier can be scaled independently to handle heavier user traffic without needing to duplicate or scale the underlying database.
2. **Security & Isolation:** The database container can remain isolated within an internal network without exposing database ports directly to the public internet.
3. **Maintainability & Modular Upgrades:** Updating or restarting the web application service does not disrupt or risk corrupting the core database process, allowing for easier maintenance[cite: 1].
