# Linux-server-Labs
Ubuntu Server NAT Configuration Lab

# Overview

This repository contains a hands-on Linux networking lab demonstrating how to configure an Ubuntu Server as a NAT Gateway for an internal network using Oracle VirtualBox.

The project covers the complete process of configuring network interfaces, enabling IP forwarding, creating NAT rules with iptables, and testing connectivity from Windows client machines.

# Lab Environment

- Operating System: Ubuntu Server
-  Virtualization: Oracle VirtualBox
- Client OS: Windows 10
- Networking: Internal Network + NAT
-  Technologies: Netplan, IP Forwarding, iptables (MASQUERADE)

# Objectives

- Configure Ubuntu Server network interfaces.
- Assign a static IP address using Netplan.
- Enable IP Forwarding.
- Configure NAT using iptables.
- Connect Windows clients through the Ubuntu gateway.
- Verify connectivity using ping tests.

# Lab Steps

Identify network interfaces and routing table.
Configure a static IP address with Netplan.
Enable IPv4 forwarding.
Configure NAT (MASQUERADE) using iptables.
Configure Windows client network settings.
Test communication between clients and the Ubuntu gateway.

# Skills Demonstrated

- Linux System Administration
- Ubuntu Server Configuration
- Netplan
- TCP/IP Networking
- Routing
- NAT Configuration
- IP Forwarding
- iptables Firewall
- VirtualBox Networking
- Windows Client Configuration
- Network Troubleshooting
  
# Lab Report

The repository includes a detailed PDF report containing:

- Configuration steps
- - Command outputs
- Screenshots
- - Network verification tests
- Final results

# Learning Outcome

After completing this lab, Ubuntu Server successfully functions as a NAT gateway, allowing Windows clients on the internal network to communicate through the gateway while demonstrating practical Linux networking and system administration skills.

## Future Plans

This repository will continue to expand with practical Linux System Administration and Network Security labs, including:

- Linux Firewall (UFW)
- - Advanced iptables Configuration
- Network Address Translation (NAT)
- - Routing and IP Forwarding
- SSH Server Configuration
- - Firewall Rules and Access Control
- Traffic Filtering
- Network Troubleshooting
- - Squid Proxy Server
- Proxy and Firewall Integration
- - pfSense Firewall
- DNS Configuration
- - DHCP Configuration
- Active Directory Integration
- - Windows Domain Services
- Group Policy (GPO)
- Asterisk Voip
Author: Samirə Məmmədova

-
