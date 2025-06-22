# 🏡 Home Server with CasaOS + Ubuntu Server

This repository documents the setup of my personal home server running Ubuntu Server, managed via [CasaOS](https://casaos.io/). It serves as a learning project to deepen my understanding of Linux systems, self-hosted tools, and home network environments.

## 🎯 Purpose

This project was created for **personal development and experimentation**. It helps me:

- Learn system administration using Ubuntu Server  
- Explore containerization via Docker  
- Understand network access and security tools like Tailscale and ZeroTier  
- Build a functional and private environment for media, storage, and multiplayer gaming

## 💡 Overview

Self-hosted services currently deployed:

- 🎞️ **Jellyfin** – Media streaming  
- ☁️ **Nextcloud** – Personal cloud storage  
- 🧲 **qBittorrent** – Torrent client  
- 🎮 **Minecraft server** – Multiplayer with friends  
- 🧩 **CasaOS** – Simple interface for app management  
- 🔒 **Tailscale** – Secure remote access (for admin)  
- 🌐 **ZeroTier** – Game networking (for friends)

## 🧰 Tech Stack

| Component    | Tool / Service            |
|--------------|---------------------------|
| OS           | Ubuntu Server 22.04 LTS   |
| UI           | CasaOS                    |
| Containers   | Docker (managed by CasaOS)|
| Remote Access| Tailscale                 |
| Game Network | ZeroTier                  |

## 🎮 Minecraft Server

- **Edition**: Java Edition  
- **Networking**: ZeroTier virtual LAN  
- **Friends connect**: Via ZeroTier IP  
- **Hosted**: Inside Docker via CasaOS  
- **Data**: Stored with persistent volumes

## 🔐 Access Strategy

- **Tailscale** allows me to securely access the server and CasaOS dashboard from anywhere  
- **ZeroTier** provides friends with seamless multiplayer connectivity without port forwarding

## 📌 To-Do

- [ ] Add HTTPS via reverse proxy (e.g., Caddy or Nginx)  
- [ ] Monitor system resources (Netdata, Glances, etc.)  
- [ ] Implement automated backups for Docker volumes and configs  
- [ ] Set up dynamic DNS or remote UI tunneling  
- [ ] Organize service logs and health checks  
- [ ] Add more storage (expand with additional HDD/SSD)  
- [ ] Develop and self-host personal apps (e.g., financial control, task manager)

## 🙌 Credits

- [CasaOS](https://casaos.io/)  
- [Tailscale](https://tailscale.com/)  
- [ZeroTier](https://www.zerotier.com/)  
- [Docker](https://www.docker.com/)  
- [Ubuntu Server](https://ubuntu.com/download/server)  
- [Minecraft Server](https://www.minecraft.net/en-us/download/server)
