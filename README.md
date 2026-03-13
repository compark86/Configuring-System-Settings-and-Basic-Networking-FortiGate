# Configuring-System-Settings-and-Basic-Networking-FortiGate

## 📋 Overview
This repository contains lab exercises for configuring basic system settings and network interfaces on FortiGate firewall. The lab is divided into two tasks.

## 🎯 Lab Objectives
- Сonfigure FortiGate to allow clients to connect to the Internet. Clients must receive their network settings using DHCP.
- Сonfigure an interface facing the local area network with the correct IP address and to act as a DHCP server.
- Сonfigure an interface facing the WAN
- Сreate a default route that uses WAN interface to forward all internet traffic to your ISP
- Verify network connectivity

## 🛠 Requirements
- FortiGate (physical or VM) with FortiOS 6.x or 7.x
- Basic knowledge of networking concepts
- Access to FortiGate CLI or GUI

## 📁 Lab Structure
- **Task1-System-Settings/** - Configuring the LAN interface, including DHCP server
- **Task2-Basic-Networking/** - Configure and monitor the default route

## 🔧 How to Use This Lab
1. Clone this repository
2. Follow the instructions in each task folder
3. Use CLI commands or GUI screenshots as reference
4. Verify your configuration with the verification steps

## 📝 Notes
- All configurations were tested on FortiOS 7.6.4
- IP addresses used are from private ranges (lab environment)
