Homelab Architecture

Overview

The homelab consists of TrueNAS server and Proxmox VE. These systems provide a foundation for storage, self-hosted services, virtual machines, and experimentation. 

The architecture is structured to be a flexible environment for learning Linux administration, networking, virutal machines, and cybersecurity.

Infrastructure

TrueNAS

TrueNAS provides centralized storage and hosts several self-hosted services. 

Primariy functions include:

- Network-attached storage
- SMB file sharing
- Self-hosted applications
- Media storage
- Photo storage
- Game server hosting

Current services include:

- Jellyfin
- Immich
- Crafty Controller
- Tailscale

Proxmox VE

Proxmox VE provides the virtualization environment used for running virtual machines and experimenting with different operating systems and configurations. 

Proxmox is used primarily for:

- VM management
- Linux environments
- Testing and experimentation 
- Cybersecurity labs
- Isolated environments

Design Goals

- Provide centralized storage for personal data and media
- Host self-hosted services for data and information privacy
- Provide a flexible virtualization environment for experimentation
- Develop practical Linux and networking skills
- Provide a controlled and isolated environment for cybersecurity learning

Future Development

The architecture will continue to evolve as new hardware, services, and environments are added.