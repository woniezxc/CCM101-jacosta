# Security Audit & Concepts Report

## Core Chapter 8 Security Concepts

### The Principle of Least Privilege (PoLP)
The Principle of Least Privilege (PoLP) dictates that user accounts, processes, and systems should only be given the absolute minimum permissions and access rights necessary to perform their specific tasks. In cloud user accounts, this is critical because it limits the blast radius; if an attacker compromises a single low-level service account, they are contained and cannot execute root-level or administrative commands across the entire cloud environment.

### Attack Surface
The attack surface of a virtual machine or cloud server refers to the sum total of all potential entry points, exposed network ports, running services, and vulnerabilities that an unauthorized user or malicious actor can exploit to gain access. When a server is left unconfigured with unnecessary open ports and unmonitored services, its attack surface expands significantly, providing more opportunities for automated scanners and brute-force bots to breach the infrastructure.

### Default Deny Policy
A Default Deny policy is a security stance where all incoming network traffic is blocked by default, and access is only permitted through explicitly approved, highly scrutinized exception rules. It is drastically safer than trying to block specific malicious actors individually because attackers constantly change IP addresses and exploit new vulnerabilities, whereas a strict deny-all baseline ensures that unauthorized traffic is blocked automatically.
