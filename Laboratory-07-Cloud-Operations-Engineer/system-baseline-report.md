# System Baseline Report

## Host Hardware Metrics
* **Total RAM Available:** 1.9Gi
* **Total Storage Capacity (Root `/` File System):** 19G

## Criticality Analysis
* **Why checking disk space is critical before a massive traffic surge:** Checking available disk space beforehand is vital because unexpected traffic surges generate heavy application access/error logging, session states, and temporary cache files that can completely fill the root file system, causing the operating system or active containerized services to crash.
