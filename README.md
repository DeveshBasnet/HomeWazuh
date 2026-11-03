# Wazuh Server on Ubuntu VM

This repository documents the deployment of a Wazuh SIEM/XDR server on an Ubuntu virtual machine for log collection, threat detection, security monitoring, and agent management.

## Environment

- Ubuntu Server 22.04 LTS
- Wazuh All-in-One Installation
- Virtual Machine Environment (VirtualBox/VMware)
- Single Node Deployment

## Components Installed

- Wazuh Manager
- Wazuh Indexer
- Wazuh Dashboard

## Installation Summary

1. Update the Ubuntu server.
2. Download the Wazuh installation script.
3. Run the all-in-one installation.
4. Verify Wazuh services are running.
5. Configure firewall rules.
6. Access the Wazuh Dashboard via HTTPS.
7. Enroll Windows and Linux agents.

## Default Ports

| Service | Port |
|----------|------|
| Dashboard | 443 |
| Agent Registration | 1515 |
| Agent Communication | 1514 |
| Wazuh API | 55000 |

## Verification

Ensure the following services are running:

- wazuh-manager

<img width="1213" height="712" alt="image" src="https://github.com/user-attachments/assets/e7664de6-35ea-4262-a595-ee002256878c" />

- wazuh-indexer

<img width="1211" height="538" alt="image" src="https://github.com/user-attachments/assets/cd222e53-703b-4f6c-b361-d1a8c618d758" />

- wazuh-dashboard

<img width="1216" height="510" alt="image" src="https://github.com/user-attachments/assets/07259b80-36ff-47dc-8156-b9c139be2d36" />


Access the dashboard:

Login Page :

<img width="1206" height="771" alt="image" src="https://github.com/user-attachments/assets/613b4bc6-a9b2-4279-9af7-271517765527" />

API Checks:

<img width="1623" height="596" alt="image" src="https://github.com/user-attachments/assets/fe004011-65cc-4970-8c97-2eaba2c2f11a" />

<img width="1222" height="521" alt="image" src="https://github.com/user-attachments/assets/f99643d6-a3da-4315-9498-9fa2fa47a740" />

Dashboard Overview:

<img width="2472" height="1232" alt="image" src="https://github.com/user-attachments/assets/72d3f2b7-c049-4afd-a26b-456c2a75f3a7" />


EndPoints :

I've added some endpoints to the Detection

<img width="2537" height="770" alt="image" src="https://github.com/user-attachments/assets/e51be0d8-d40b-447b-9efe-4715dc195c39" />

Event Search: 

<img width="2492" height="1242" alt="image" src="https://github.com/user-attachments/assets/77f293cd-27c3-4686-861c-c5eb885d609d" />




## Features

- Centralized Log Management
- Threat Detection
- File Integrity Monitoring (FIM)
- Vulnerability Detection
- Security Event Monitoring
- Agent Management


## References

- https://documentation.wazuh.com
- https://github.com/wazuh/wazuh

## Author


