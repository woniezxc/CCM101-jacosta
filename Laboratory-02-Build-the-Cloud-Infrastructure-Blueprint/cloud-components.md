# Cloud Infrastructure Components Analysis

## 1. Compute Resources
* **Purpose:** Compute resources provide the processing power required to run operating systems, execute code, and perform calculations.
* **Importance in Cloud Computing:** They allow applications to process data dynamically without needing physical hardware on-site, enabling instant scaling based on user demand.
* **KillerCoda Relation:** In the KillerCoda environment, compute is provided via a virtualized single-core Intel Xeon CPU @ 2.0GHz and 1.9 GiB of RAM allocated to our instance.

## 2. Storage Resources
* **Purpose:** Storage resources hold persistence data, operating system files, logs, and application files long-term.
* **Importance in Cloud Computing:** High-availability storage ensures data persistence across server reboots, backup creation, and scalable storage expansion.
* **KillerCoda Relation:** Represented by the virtual disk partition `/dev/vda1` providing 19 GB of root storage mounted on `/`.

## 3. Networking Resources
* **Purpose:** Networking enables communication between cloud instances, external internet clients, and internal microservices.
* **Importance in Cloud Computing:** Defines security boundaries, route management, public/private access, and load distribution across services.
* **KillerCoda Relation:** Represented by network interface `enp1s0` with local IP address `172.30.1.2` and loopback interface `lo`.

## 4. Operating System
* **Purpose:** The operating system acts as the core interface between physical/virtualized hardware and running software applications.
* **Importance in Cloud Computing:** OS platforms like Linux provide light, secure, highly modular environments designed specifically for running cloud-native containers and microservices.
* **KillerCoda Relation:** The instance runs Linux Kernel `6.8.0-138-generic` on top of an `Ubuntu 24.04 LTS` distribution.
