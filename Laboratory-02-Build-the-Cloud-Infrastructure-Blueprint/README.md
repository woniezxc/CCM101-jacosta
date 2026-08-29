# Laboratory Activity 2: Build the Cloud Infrastructure Blueprint

## Mission Overview
This laboratory activity focuses on investigating the fundamental components of cloud infrastructure using a Linux-based virtual machine in the KillerCoda environment. The goal is to inspect hardware specifications, analyze infrastructure roles, compare major cloud provider services, design a cloud architecture blueprint, and produce structured technical documentation.

## Objectives
* Investigate hardware and software resources in a live Linux environment.
* Identify and explain compute, storage, networking, and operating system components.
* Compare equivalent services across AWS, Microsoft Azure, and Google Cloud Platform (GCP).
* Design a basic cloud infrastructure architecture diagram.
* Maintain professional technical documentation using Markdown in GitHub.

## Cloud Infrastructure Components
* **Compute:** Intel Xeon CPU (1 core @ 2.0GHz) with 1.9 GiB RAM for workload processing.
* **Storage:** 19 GB root disk partition (`/dev/vda1`) mounted on `/`.
* **Networking:** Virtual network interface (`enp1s0`) assigned with IP `172.30.1.2`.
* **Operating System:** Ubuntu 24.04 LTS running Linux Kernel `6.8.0-138-generic`.

## Tools Used
* **KillerCoda Playground:** Linux terminal sandbox.
* **GitHub:** Version control and portfolio hosting.
* **Draw.io:** Cloud infrastructure diagramming tool.

## Linux Commands Executed
* `uname -r` - Displays kernel release version.
* `lscpu` - Gathers detailed CPU architecture information.
* `free -h` - Displays available and used RAM memory.
* `df -h` - Checks disk space usage and mounted file systems.
* `hostname` - Identifies system host name.
* `ip a` - Displays active network interfaces and IP addresses.

## Skills Learned
* Investigating cloud server specifications using Linux command-line tools.
* Mapping hardware resources to core cloud computing concepts.
* Evaluating public cloud ecosystem services across AWS, Azure, and GCP.
* Diagramming cloud architectures and structuring technical Markdown reports.

## Challenges Encountered
* Accurately interpreting Linux command outputs for CPU architecture and disk partition layouts, which was resolved by reviewing system documentation.
