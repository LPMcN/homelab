# Homelab Networking

## Overview

The homelab network provides connectivity between servers, virtual machines, personal devices, and self-hosted services.

The network is used to develop practical experience with IP addressing, switching, VLANs, DNS, file sharing, and remote access.

## Network Components

The primary networking components include:

- Router
- Network switch
- TrueNAS server
- Proxmox VE
- Virtual machines
- Personal devices

## IP Addressing

The homelab uses private IP addressing for communication between devices and services.

Static IP addresses are assigned to infrastructure that requires consistent network connectivity, such as servers and other network services.

Sensitive addressing information is intentionally excluded from this repository.

## Switching

The network switch provides connectivity between the homelab servers and other network devices.

Switching is used to provide reliable connectivity between:

- TrueNAS
- Proxmox
- Personal computers
- Other network devices

## VLANs

VLANs are used to logically separate network traffic where appropriate.

They provide an opportunity to practice:

- Network segmentation
- VLAN configuration
- Inter-VLAN communication
- Access control
- Network troubleshooting

## Network File Sharing

SMB/Samba is used to provide network file sharing between the TrueNAS server and client devices.

This allows files stored on the server to be accessed by authorized devices across the network.

## Remote Access

Tailscale provides remote access to selected homelab resources when access from outside the local network is required.

Remote access is configured to limit exposure of services directly to the public internet.

## Network Security

Network security is an important part of the homelab and provides an environment for practicing defensive networking concepts.

Areas of focus include:

- Network segmentation
- Access control
- Firewall configuration
- Secure remote access
- Service isolation
- Traffic monitoring
- Network troubleshooting

## Future Development

Potential future networking projects include:

- Additional VLAN segmentation
- Improved network monitoring
- Expanded firewall rules
- Network traffic analysis
- Additional isolated lab networks
- Automated network configuration
- Improved network documentation