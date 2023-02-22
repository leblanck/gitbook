---
description: How Pi-Hole is Set up in GCP and On-Prem
---

# 🕳 Pi-Hole

## Intro

As of writing this we have 2 Pi-Hole setups, one "on-prem" and one in Google Cloud. The "on-prem" version is running a Raspberry Pi 3B+.&#x20;

## On-Prem

Pi-Hole GUI Access

1. Go to either http://redpoint-locke/admin OR http://192.168.1.251/admin
2. Admin credentials are in 1Password

Pi-Hole Console Access

1. SSH into `redpoint-locke` as pi user:
   1. ssh pi@redpoint-locke
   2. Credentials for pi user are in 1Password

## Google Cloud

Pi-Hole GUI Access

1. Connect to VPN. See [VPN Doc.](vpn.md)
2. Go to: [http://10.66.66.1/admin/](http://10.66.66.1/admin/)

Pi-Hole Console Access

1. Set Up `gcloud` cli (See [GCP CLI Doc](../setting-up-google-cloud-project-cli-sdk.md))
2. SSH into `pi-hole` instance: `gcloud compute ssh pi-hole` (Only omit Zone and Project if defaults are set)

## Updating

Occasionally you will need to update PiHole. If you see an update is needed when in the GUI or console then you should update as soon as possible.

To Update:

1. Follow the above instructions for getting into the correct instance (GCP or On-Prem) for console access.&#x20;
2. Issue the following command:
   1. `pihole -up`
   2. If any issues arise, resolve as necessary.

