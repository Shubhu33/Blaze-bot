# 🔥 BlazeNodes VPS Maker Bot

BlazeNodes is a **Discord VPS Maker Bot** that lets you create and manage VPS servers directly inside Discord.  
It supports both **Docker VPS** (with instant SSH via tmate) and **Pterodactyl VPS** (via Application API).  

Perfect for hosting providers, gaming communities, and anyone who wants **on-demand VPS hosting inside Discord**.  

---

## ✨ Features

- 🚀 **Deploy VPS**
  - `/deploy` → Create a Docker VPS (Ubuntu/Debian with SSH).
  - `/deploy-ptero` → Create a Pterodactyl VPS on your panel.

- 🔧 **Manage VPS**
  - `/list` → View all your VPS instances with interactive buttons:
    - ▶ Start  
    - ⏹ Stop  
    - 🔄 Restart  
    - 🗑 Delete  
  - `/regen-ssh` → Regenerate SSH session for Docker VPS.

- 📆 **Expiry System**
  - VPS auto-expires after the set duration (e.g., `1d`, `2h`).
  - Automatic cleanup of Docker/Pterodactyl instances.
  - DM notification when your VPS is removed.

- 🛡️ **Admin Controls**
  - Resource limits (RAM/CPU caps).
  - Admin-only deployment by default.
  - Full logging & error handling.

---

## 📂 Project Structure

