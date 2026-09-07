# Virtual Machine Setup --> Kali Linux

OVERVIEW

This readme details the setup of Kali Linux virtual machine running on Oracle VirtualBox. This is built for hands on experience learning in cybersecurity, networking practice, penetration testing and much more.

# Technical Specifications

| Component | Host System (Windows 11) | Guest VM (Kali Linux) |
| :--- | :--- | :--- |
| **CPU** | Intel Core i3-1114G4 | 2 Cores |
| **RAM** | 8 GB | 4 GB |
| **Storage** | 477 GB SSD | 30 GB+ (Dynamically Allocated VDI) |
| **Network** | Physical LAN | NAT |

# Setup and Installation Part

1. Open VirtualBox and select New
2. Name the OS to Kali Linux and choose version Debian (64bit)
3. Assign 4 GB RAM and 2 CPU Cores
4. Create a 30 GB+ VDI drive ( Allocated Dynamically)
5. Mount the Kali Linux Installer ISO and start the Virtual Machine
6. Select Graphic Installer

# After Installation 

Go to terminal and write sudo apt update && sudo apt full-upgrade -y

## IMPORTANT

# THIS SETUP IS STRICTLY FOR AUTHORIZED TESTING AND EDUCATIONAL LABS ONLY. PRACTICE TOOLS ON AN INTERNAL / HOST ONLY NETWORK NOT ON A BRIDGED INTERNET CONNECTION #
