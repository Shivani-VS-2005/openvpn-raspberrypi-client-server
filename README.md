# Secure VPN Client-Server Communication Using OpenVPN

## Overview

This project demonstrates secure communication between a Windows PC and a Raspberry Pi using OpenVPN. A client-server architecture was implemented to establish an encrypted VPN tunnel, enabling secure remote connectivity and device management.

## Architecture

```text
Windows PC (OpenVPN Server)
            │
            │ Encrypted VPN Tunnel
            │
Raspberry Pi (OpenVPN Client)
```

## Features

* Secure VPN communication using OpenVPN
* Client-server architecture implementation
* Remote access to Raspberry Pi
* Encrypted data transmission
* SSH access using MobaXterm
* Virtual tunnel interface (`tun0`) for secure networking

## Technologies Used

* Raspberry Pi OS
* OpenVPN
* Windows
* MobaXterm
* SSH
* Linux Networking

## Project Workflow

1. Configure the Windows PC as the OpenVPN server.
2. Install and configure OpenVPN on the Raspberry Pi.
3. Establish a secure VPN tunnel between both devices.
4. Verify the connection using the `tun0` interface and ping commands.
5. Access and manage the Raspberry Pi remotely through SSH.

## Commands Used

### Install OpenVPN on Raspberry Pi

```bash
sudo apt update
sudo apt install openvpn -y
```

### Check VPN Interface

```bash
ip addr show tun0
```

### Check OpenVPN Status

```bash
sudo systemctl status openvpn
```

### Verify Connectivity

```bash
ping 10.8.0.1
```

## Applications

* Embedded Systems
* Internet of Things (IoT)
* Remote Device Management
* Secure Communication
* Industrial Monitoring
* Network Administration

## Learning Outcomes

Through this project, I gained practical experience in:

* OpenVPN configuration
* Client-server architecture
* Linux networking fundamentals
* VPN tunnel interfaces (`tun0`)
* Remote access using SSH
* Secure communication concepts

## Folder Structure

```text
secure-vpn-client-server-using-openvpn/
│
├── README.md
├── screenshots/
├── docs/
└── commands-used.md
```

## Author

Shivani Vijayachandran

---

This project helped strengthen my understanding of networking, Linux administration, and secure communication in embedded and IoT environments.
