#### Our notes to use along with the official Harmony ONE Validator documentation
---

# Linux Server Node Setup

## Server Requirements

Here's the current recommended hardware from Harmony Foundation:

![From the official Harmony Guide 9/12/2021](../../public/image_20.png)

### Storage

Before we talk about providers let's discuss storage. Make sure you have enough space as we're currently adding over 25GB a month due to transaction increases.

![Database Sizes on 9/12/2021](../../public/image_24.png)

Digital Ocean has the option to use "Volumes" that can be [easily expanded](https://docs.digitalocean.com/products/volumes/how-to/increase-size/) when more space is required to help with cost savings.

## Cloud Server Providers

### Digital Ocean

We use [Digital Ocean](https://m.do.co/c/b761e5fdd694). You're free to use anyone you'd like but our guide is written for **Ubuntu 20.04 LTS on Digital Ocean** although it may work just fine with any Ubuntu release or provider.

Here are the suggested node requirements as of 9/12/2021:

![CPU Optimized Servers](../../public/image_23.png)

### Vultur

We've begun testing with [Vultur](https://www.vultr.com/?ref=8873853) as an alternative and cost savings.

The official guide has server suggestions but here's ours:

Server Location: Silicon Valley  
Server Type: Use recommendations above  
SSH Keys: Load your Public SSH key for easy access to the root account  
Firewall Group: Setup the [Vultr Firewall settings in the official guide](https://docs.harmony.one/home/network/validators/cloud-setup/cloud-guides/vultr#firewall-setup)  
Server Hostname: Set a hostname of your liking  
  
SSH into your host using the root account to begin setup.

### Our only referrals in this guide - Get $100 Free off Server Fees on either provider!

If you sign up with [Digital Ocean](https://m.do.co/c/b761e5fdd694) or [Vultr](https://www.vultr.com/?ref=8873853) using our links you'll get $100 in credit towards your future server fees.

You can try other providers but they will cost you a lot more. We hear Vultr is good but haven't investigated them or their setup yet.

### OVH & OVH.us

We currently run a bare metal advanced-2 server from OVH.us for our 2nd and testing node. You get quite the discount for pre-paying for a year of service. Worth looking into if you are on a budget but requires some manual setup of things as you are the full administrator of an empty server to start.  
  
**Warning:** AWS, Google & Microsoft will probably cost you far more than you will make at this point.
