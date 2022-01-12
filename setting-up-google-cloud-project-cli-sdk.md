---
description: Follow this guide to use GCP command line locally
---

# Setting Up Google Cloud Project CLI (SDK)

Prerequisites:&#x20;

* Pyhon 3
* iTerm2 with powerline 10k ;)&#x20;

![Hint: when you have the GCP SDK & Powerline 10K installed with a default project, as soon as you type gcloud, your default project will appear so you always know where you are in GCP project space](<.gitbook/assets/Screen Shot 2022-01-12 at 3.20.54 PM.png>)

Download and extract the sdk install from the link below:&#x20;

{% embed url="https://cloud.google.com/sdk/docs/quickstart" %}
SDK Download link and full install instructions
{% endembed %}

**Follow the default instructions/values and make sure that the default project is set to `pihole-vpn` and the default zone is set to `us-east1-b`**

To SSH into an instance you can run the following (provided the defaults were set up correctly above, or if they have not changed):

`gcloud compute ssh $INSTANCE_NAME`

{% embed url="https://cloud.google.com/compute/docs/instances/connecting-to-instance#gcloud" %}
More SSH instructions
{% endembed %}
