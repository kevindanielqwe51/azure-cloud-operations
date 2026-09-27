\# Azure Cloud Operations Lab



\## Overview



This project simulates a small production-style Azure environment focused on secure network segmentation, private workloads, Linux administration, and cloud troubleshooting.

## Architecture

The environment is divided into three network segments:

- **Management subnet (10.10.1.0/24)** — Hosts the administrative VM used as a jump host for SSH access.
- **Web subnet (10.10.3.0/24)** — Hosts a Linux web server running Apache.
- **Backend subnet (10.10.4.0/24)** — Hosts a private backend VM.

The Web and Backend VMs use private IP addresses and are not directly exposed to the Internet.

### Azure Components

- Azure Virtual Network
- 3 Subnets
- 3 Network Security Groups
- 3 Linux Virtual Machines
- NAT Gateway
- Private DNS Zone
- Apache Web Server
- SSH
