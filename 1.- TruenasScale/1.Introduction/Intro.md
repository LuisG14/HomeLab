# TrueNAS Scale Project

This repository documents the installation, configuration, and applications I use on my **TrueNAS Scale** server.  
The goal is to have a stable and scalable self-hosted storage and services system that allows me to manage data and applications easily, and that serves as the foundation for my home lab, which is in constant growth and focused on learning new tools.

## Why TrueNAS Scale?
I chose **TrueNAS Scale** because:
- It supports installing a wide variety of applications, from multimedia to productivity and development tools.
- With **Nextcloud**, I can offer my family an easy way to upload images and videos to their own partition within my storage space.
- Its administration system allows me to **partition and organize disks** flexibly, assigning space according to specific needs.
- It includes **Docker**, giving me the freedom to deploy custom services.
- It is perfect for my home lab, aiming for constant growth and learning with different tools.

## Problems it solves
Before using TrueNAS Scale:
- My family used different devices to back up data:
  - My father used a laptop, but ran out of space, so I had to lend him storage.
  - My mother used an external hard drive that I knew would eventually fail, and I didn’t want her to lose photos and videos she has kept for over **26 years**.
- I was also running out of space on all my devices, plus a nearly full external hard drive, which would have forced me to pay for cloud storage (something I wanted to avoid).

With TrueNAS Scale I now have:
- A **centralized NAS** where we can all store data securely.
- Simple access for my family and friends, with dedicated partitions for each.
- Self-hosted applications such as Plex, Nextcloud, Ollama, and more.
- Automatic backups and secure remote access via Tailscale.

## Repository structure
- **Config and Specs** → Initial and technical configurations (notifications, SSH, disks, dashboard).
- **Apps** → Documentation and configuration for each installed application.
- **Future** → Plans and experiments for the future (external backups, VMs, etc.).

> This project is still in development and will continue to grow as I add more services to my environment and gain experience with different technologies.
