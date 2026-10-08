# Homelab Storage

## Overview

The homelab uses TrueNAS as the primary storage platform.

TrueNAS provides centralized storage for media, photos, application data, and network file sharing. Storage is also accessed by services running on the homelab infrastructure.

## Storage Architecture

TrueNAS provides centralized storage for several types of data:

- Media files
- Photos
- Application data
- Minecraft server data
- Shared files
- Backup data

Services access storage through datasets, mounts, and network shares as appropriate.

High-level storage architecture:

```text
                    TrueNAS
                       |
        +--------------+--------------+
        |              |              |
     Media          Photos       Application
        |              |              |
     Jellyfin        Immich       Other Services
        |
     SMB Shares
        |
   Client Devices