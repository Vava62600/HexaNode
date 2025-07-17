# HexaNode

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Project Status](https://img.shields.io/badge/status-active-brightgreen)](#)
[![Language](https://img.shields.io/badge/languages-HTML%20%7C%20PHP%20%7C%20CSS%20%7C%20JS-orange)](#)
[![Latest Release](https://img.shields.io/badge/release-v1.0.0-blueviolet)](#)
[![Open Source](https://img.shields.io/badge/opensource-yes-green)](#)

---

## 🧠 About the Project

**HexaNode** is a modular, web-based operating system designed for servers, combining the functionalities of Proxmox, TrueNAS Core, and Docker into a unified, open-source, modern, and user-friendly platform.

It allows managing:
- Virtual machines (QEMU/KVM),
- Docker containers,
- Storage (ZFS, EXT4, NTFS, USB drives, RAID),
- Network services (reverse proxy, firewall, VLAN),
- Home automation (Home Assistant and others),
- System services and users,
- Application deployment via a web AppStore.

HexaNode is built for enthusiasts, makers, developers, and system administrators who want **maximum control with a modern UI**.

---

## 🌍 Supported Languages

- 🇬🇧 English
- 🇫🇷 French  
_(others can be added easily via translation modules)_

---

## 🔧 Technologies & Libraries Used

| Category                | Tools / Libraries / Services                   |
|------------------------|-------------------------------------------------|
| **Web Stack**           | HTML, CSS, JavaScript, PHP                     |
| **Frontend Framework** | VanillaJS + Custom SPA Loader + Dynamic Router |
| **UI**                  | Custom theming engine (light/dark/themes)      |
| **Auth System**         | Token-based Auth, Browser/IP Fingerprinting    |
| **Hypervisor**          | QEMU, KVM, Libvirt, VirtIO                     |
| **Containers**          | Docker, Podman (optional)                      |
| **Storage**             | ZFS, EXT4, NTFS, Btrfs, mdadm (RAID), USB      |
| **Network**             | Apache2, Reverse Proxy (mod_proxy), ufw/iptables |
| **Automation**          | Home Assistant Core, MQTT, Node-RED (optional) |
| **System Services**     | systemd, cron, rsyslog, SSH, Avahi, SMB, NFS   |
| **VM Display**          | WebSocket support for live VM preview          |
| **Packaging**           | ZIP, JSON for VM & container export/import     |

---

## 💡 Key Features

- Web interface with real-time dynamic loading (SPA)
- No page reloads, full API integration
- Built-in reverse proxy per app (`/appname`)
- VM snapshot, share, import/export (with metadata + disk)
- Custom plugin/theme system
- Full logs and alert system
- Secure login with IP and browser detection
- Token auto-renewal + intrusion detection

---

## 📦 Latest Release

**v1.0.0**  
Initial public release (MIT licensed, stable and functional)

---

## 🔓 License

HexaNode is released under the **MIT License** — you are free to use, modify, and distribute it, even commercially.  
See the [LICENSE](./LICENSE) file for more info.

---

## ⭐ GitHub Stars

If you like the project, don't forget to **star** it — it helps visibility and shows support to the community.

---
