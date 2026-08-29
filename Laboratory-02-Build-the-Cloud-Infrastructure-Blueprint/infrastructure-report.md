# Infrastructure Assessment Report

## System Overview
* **Operating System:** Ubuntu 24.04 LTS
* **Kernel Version:** 6.8.0-138-generic
* **Hostname:** ubuntu
* **IP Address:** 172.30.1.2 (Interface: enp1s0)

## Compute Resources
* **CPU Model:** Intel Xeon E312xx (Sandy Bridge, IBRS update) @ 2.0GHz
* **Number of CPU Cores:** 1 Core (1 Thread)
* **Total RAM:** 1.9 GiB (approx. 2 GB)

## Storage & File Systems
* **Disk Capacity:** 19 GB (Root partition `/dev/vda1`)
* **Mounted File Systems:**
  * `/` (Root filesystem on `/dev/vda1` - 19G)
  * `/boot` (Boot filesystem on `/dev/vda16` - 881M)
  * `/boot/efi` (EFI filesystem on `/dev/vda15` - 105M)
  * `tmpfs` (Temporary memory filesystems mounted on `/run`, `/dev/shm`, `/run/lock`)
