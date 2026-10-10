# Secure Two-Site Network Simulation with GNS3

## Project Overview

This project focuses on designing and simulating a secure network connecting two sites using GNS3.

The objective is to enable communication between the two sites while implementing dynamic routing and secure communication through an IPsec site-to-site VPN.

## Technologies Used

- **GNS3** — Network topology simulation
- **FortiGate** — Firewall configuration and network security
- **OSPF** — Dynamic routing between network devices
- **IPsec VPN** — Secure communication between the two sites
- **RADIUS / FreeRADIUS** — Centralized authentication
- **Wireshark** — Network traffic analysis

## Main Objectives

- Configure routing between the two sites using OSPF.
- Establish an IPsec site-to-site VPN.
- Configure firewall policies to control network traffic.
- Implement centralized authentication using RADIUS.
- Analyze VPN traffic using Wireshark.

## Project Files

- `Projet_Stage.gns3` — GNS3 project configuration.
- `wireshark-ipsec-vpn-capture.png` — Screenshot of VPN traffic analysis in Wireshark.
- `topology.png` - Screenshot of the project topology.

## Requirements and Limitations

The GNS3 project file may reference external appliance images and virtual machines that are not included in this repository. These must be installed and configured separately, subject to their licensing requirements.

## Author

Network security and infrastructure simulation project.
