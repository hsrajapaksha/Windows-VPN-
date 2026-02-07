# Windows VPN Dial-Up Implementation  
### Windows Server 2025 & Windows 11

## Overview
This project demonstrates a complete **VPN (Dial-Up) implementation** using **Windows Server 2025** as the VPN server and **Windows 11** as the client. The setup uses **RRAS**, **PPTP VPN**, **router port forwarding**, and a **load balancer** to provide secure remote access.

This repository is intended for **educational, lab, and small enterprise use**.





---

## Technologies Used
- Windows Server 2025 (RRAS)
- Windows 11 VPN Client
- PPTP VPN (TCP Port 1723)
- Active Directory
- Internet Router (Port Forwarding)
- Load Balancer




---

## Features
- VPN server configuration using RRAS
- Dial-up VPN client setup on Windows 11
- User-based VPN access control
- Static or DHCP IP address assignment
- Router port forwarding (TCP 1723)
- Load balancer traffic forwarding to VPN server
- Simple and clear network connectivity design





---

## Network Flow
VPN Client → Internet → Router (Port 1723) → Load Balancer → VPN Server → Internal Network



---

## How to Use
1. Configure RRAS on Windows Server 2025
2. Enable VPN access for users
3. Forward TCP port 1723 on the internet router
4. Configure load balancer to forward traffic to VPN server
5. Create VPN connection on Windows 11 client
6. Test VPN connectivity

<img width="1841" height="882" alt="vpn connection 2 " src="https://github.com/user-attachments/assets/4505509b-4a12-4623-844f-b2e27adf339c" />


---
