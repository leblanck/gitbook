---
description: How to Use WireGuard VPN
---

# VPN

## Intro

We currently use [WireGuard VPN](https://www.wireguard.com) for Split-Tunnel VPN traffic. When connected to VPN, Pi-Hole will be used for DNS. [See the Pi-Hole Doc for more info. ](pi-hole.md)

### Adding New WireGuard Clients

1. SSH into `pi-hole` instance in GCP. (See Setting up GCP CLI Doc)
2. Run `sudo su -`
3. Run `./setup.sh` from the root user root directory.
4. Save either the QR Code for iOS devices, or export the data in the created `.conf` file for use in the WireGuard macOS/Windows Client

### Connecting to WireGuard

1. Download/install the WireGuard client for your approprate platform.&#x20;
2. Either Scan your saved QR Code or import the created `.conf` file.&#x20;
3. Allow the adding of VPN Network Interfaces
4. Connect to VPN
