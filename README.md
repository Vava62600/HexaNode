  # HexaNode
<p align="center">

<br>
  <a href="https://github.com/vava62600/HexaNode/stargazers">
    <img src="https://img.shields.io/github/stars/vava62600/HexaNode?style=for-the-badge" alt="GitHub stars">
  </a>
  <a href="https://github.com/vava62600/HexaNode/releases">
    <img src="https://img.shields.io/github/v/release/HexaNode/KeybMacro?style=for-the-badge" alt="Latest release">
  </a>
  <a href="https://opensource.org/license/mit">
    <img src="https://img.shields.io/badge/license-MIT-darkgreen.svg?style=for-the-badge" alt="Licence">
  </a>
  <a href="https://github.com/vava62600/HexaNode/releases">
    <img src="https://img.shields.io/badge/languages-HTML%20%7C%20PHP%20%7C%20CSS%20%7C%20JS-orange?style=for-the-badge" alt="Languages">
  </a>
</p>

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
| **Containers**          | Docker,LXC , Podman (optional)                 |
| **Storage**             | ZFS, EXT4, NTFS, Btrfs, mdadm (RAID), USB      |
| **Network**             | Apache2, Reverse Proxy (mod_proxy), ufw/iptables |
| **Automation**          | Home Assistant Core, MQTT,                     |
| **System Services**     | systemd, cron, rsyslog, SSH, Avahi, SMB, NFS, RSync, FTP, LDAP, ...  |
| **VM Display**          | WebSocket support for live VM preview          |
| **Packaging**           | ZIP, JSON for VM & container export/import     |
| **Apps Includes**       | Nextcloud, Syncthing, Pi-Hole, ...             |
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
- 
---

## 🔓 License

HexaNode is released under the **MIT License** — you are free to use, modify, and distribute it, even commercially.  
See the [LICENSE](./LICENSE) file for more info.

---

## ⭐ GitHub Stars

If you like the project, don't forget to **star** it — it helps visibility and shows support to the community.

---
