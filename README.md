# pfSense Firewall Configuration and Network Segmentation

## Project Overview

This project was completed as part of a hands-on network security lab. The objective was to configure firewall interfaces using pfSense and verify network connectivity and remote access.

The lab involved configuring WAN, LAN, and DMZ interfaces, testing connectivity, configuring split DNS, and enabling secure remote access through SSH.

## Tools and Technologies

- pfSense Firewall
- Virtualized Windows Environment
- TCP/IP Networking
- DNS and DNS Resolver
- SSH (Secure Shell)
- ICMP and Ping
- nslookup

## Project Objectives

1. Plan and configure WAN and LAN firewall interfaces.
2. Configure a DMZ interface for network segmentation.
3. Verify network connectivity using ICMP requests.
4. Configure split DNS using host overrides.
5. Verify DNS resolution using nslookup.
6. Enable and test SSH remote access to pfSense.

## Implementation

### 1. WAN and LAN Configuration

Planned the physical configuration of the firewall and configured WAN and LAN interfaces using the pfSense web interface.

Verified that both interfaces appeared on the pfSense dashboard.

### 2. DMZ Configuration

Configured a DMZ interface in pfSense as part of a segmented network environment.

Verified that the DMZ interface was active and accessible.

### 3. Network Connectivity Testing

Performed ICMP tests to verify connectivity to the upstream gateway, WAN interface, and DMZ interface.

### 4. Split DNS Configuration

Configured DNS Resolver host overrides for internal systems.

Used nslookup to verify that the configured hostnames resolved to their intended IP addresses.

### 5. SSH Remote Access

Enabled SSH access in pfSense and successfully established an SSH connection to the firewall.

## Project Results

- Successfully configured WAN, LAN, and DMZ interfaces.
- Verified connectivity using ICMP tests.
- Configured DNS host overrides and confirmed name resolution.
- Enabled SSH and verified remote connectivity.

## Skills Demonstrated

- Firewall administration
- Network interface configuration
- Network segmentation concepts
- DNS configuration and troubleshooting
- Remote system administration
- Network connectivity testing

## Key Takeaways

This lab helped me develop practical experience configuring and verifying firewall interfaces. It also reinforced my understanding of network segmentation, DNS resolution, and secure remote administration.

## Project Context

This project was completed as an academic hands-on lab for *Network Security, Firewalls, and VPNs*. The screenshots document the configuration and verification tasks performed in the lab.
