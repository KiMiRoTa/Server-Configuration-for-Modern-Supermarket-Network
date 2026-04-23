# Server-Configuration-for-Modern-Supermarket-Network

## Overview 
This project demonstrate the design and implementation of a server-based network infrastructure for a modern supermarket environment.

it focuses on configuring essential services:
- DHCP Server (Dynamic IP allocation)
- DNS Server (Domain resolution)
- Web Server (Service access)
- Database Server (Data maagement)

The goal is to simulate a real-world supermarket system where multiple services work together in a controller network.

## Network Architecture
![IPTable](./Images/IPTable.png)
- PC 1 - DHCP Server automatically assigns IP addresses to other devices in the network.
- PC 2 - DNS Server translate domain names into IP addresses to make them more accessible.
- PC 3 - Web Server provides web-based services, such as supermarket information systems.
- PC 4 - Database Server stores and manages important data such as stock of goods and transactions.
- PC 5 - These devices are used by users to access services from existing servers.

## Technologies Used
- Red Hat Enterprise Linux (RHEL 9)
- Windows XP (Client testing)
- VirtualBox
- MariaDB (Database Server)
- Apache HTTP Server (Web Server)
- DHCP and DNS services

## Server Configuration
### DHCP Server
![NanoDHCP](./Images/NanoDHCP.png)
