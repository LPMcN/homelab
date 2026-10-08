# Homelab Services

## Overview

The homelab hosts many self-hosted services for photo management, media management, game server administration, and remote VPN access. 

Services are hosted through TrueNAS with Docker. Aditional workloads are ran through Proxmox VMs.

## Services

| Service | Purpose | Platform |
|---|---|---|
| Jellyfin | Media streaming | TrueNAS |
| Immich | Photo management | TrueNAS |
| Crafty Controller | Minecraft server management | TrueNAS |
| Tailscale | Remote access | TrueNAS |

---

## Jellyfin

Jellyfin is used as a media streaming platform for the homelab.

### Purpose

- Stream DVD and Blu-Ray rips
- Organize peronsal media library
- Practice self-hosted application management
- Experiment with hardware-accelerated media processing

### Infrastructure

- Jellyfin is hosted on the TrueNAS server and accesses media stored on the server.

### Hardware Acceleration

The server includes an AMD Radeon R9 290 GPU that can be used for media processing where supported.

---

## Immich

Immich is used for self-hosted photo management.

### Purpose

- Organize personal photos
- Provide a self-hosted alternative to cloud photo services
- Practice application deployment and storage management

Immich stores its data on the TrueNAS infrastructure.

---

## Crafty Controller

Crafty Controller is used to manage Minecraft servers.

### Purpose

- Manage Minecraft server instances
- Start and stop servers
- Monitor server activity
- Manage server files and configurations
- Experiment with game server administration

Crafty provides a centralized interface for managing Minecraft server workloads.

---

## Tailscale

Tailscale provides secure remote connectivity to selected homelab resources.

### Purpose

- Remote access to homelab services
- Secure connectivity between trusted devices
- Reduce the need to expose services directly to the public internet

Tailscale is used as part of the homelab's remote-access strategy.

---

## Service Management

Services are managed through the underlying TrueNAS infrastructure and their respective application interfaces.

Management tasks include:

- Application deployment
- Configuration
- Storage allocation
- Network configuration
- Updates
- Troubleshooting
- Access control

---

## Security Considerations

Self-hosted services introduce security considerations that are addressed as part of the homelab.

Areas of focus include:

- Authentication
- Access control
- Network segmentation
- Secure remote access
- Service isolation
- Software updates
- Storage permissions
- Minimizing public internet exposure

---

## Future Development

Potential future improvements include:

- Additional self-hosted services
- Improved service monitoring
- Centralized logging
- Container security
- Service-specific network segmentation
- Automated backups
- Infrastructure documentation