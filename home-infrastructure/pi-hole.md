---
description: How Pi-Hole is Set up in GCP
---

# Pi-Hole

Intro

As of writing this we have 2 Pi-Hole setups, one "on-prem" and one in Google Cloud. The "on-prem" version is running a Raspberry Pi 3B+.&#x20;



Pi-Hole GUI Access

1. Connect to VPN. See [VPN Doc.](vpn.md)
2. Go to: [http://10.66.66.1/admin/](http://10.66.66.1/admin/)

Pi-Hole Console Access

1. Set Up `gcloud` cli (See [GCP CLI Doc](../setting-up-google-cloud-project-cli-sdk.md))
2. SSH into `pi-hole` instance: `gcloud compute ssh pi-hole` (Only omit Zone and Project if defaults are set)

