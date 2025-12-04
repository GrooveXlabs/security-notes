# 🌐 Networking Basics (Groovexlabs Notes)

These are quick notes to understand basic networking concepts that are important for cybersecurity.

---

## 1. What is a Network?

A **network** is a group of connected devices that can communicate with each other.

- Devices = computers, phones, servers, routers, etc. 
- They communicate using **IP addresses** and **ports**.

---

## 2. IP Address (Internet Protocol Address)

An IP address identifies a device on a network.

- Example IPv4: `192.168.1.10`
- Example public IP: `8.8.8.8` (Google DNS)

Types:
- **Private IP** – used inside local networks (like home Wi-Fi).
- **Public IP** – visible on the internet.

---

## 3. Ports

A **port** is like a “door” or “channel” for specific network services.

Common ports:
- `22` – SSH
- `80` – HTTP (web)
- `443` – HTTPS (secure web)
- `53` – DNS
- `25` – SMTP (email)

You already used ports in your **Simple Port Scanner** project 😉

---

## 4. TCP vs UDP

- **TCP** – connection-based, reliable, slower  
  Example: web browsing, SSH
- **UDP** – connectionless, faster, no guarantee  
  Example: video streaming, DNS queries

---

## 5. Basic Commands (Linux / Windows PowerShell)

```bash
ping 8.8.8.8        # Check if host is reachable
tracert 8.8.8.8     # Windows: trace route to a host
traceroute 8.8.8.8  # Linux: trace route
nslookup google.com # DNS lookup

More networking topics to add later:
- Subnets & CIDR (e.g. 192.168.1.0/24)
- Firewalls & NAT
- VPN basics
