#Proxmox Login Notifier

A Python script to monitor SSH and Proxmox web login attempts in real-time and send notifications via Discord.

---

## Features

- Monitors **SSH login attempts** (successful and failed).
- Monitors **Proxmox Web GUI login attempts**.
- Sends notifications to a **Discord channel** via webhook.
- Displays **timestamp, IP, and username** (root for web logins).
- Runs continuously in the background.
