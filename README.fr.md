# HexaNode
<p align="center">

<br>
  <a href="https://github.com/vava62600/HexaNode/stargazers">
    <img src="https://img.shields.io/github/stars/vava62600/HexaNode?style=for-the-badge" alt="GitHub stars">
  </a>
  <a href="https://github.com/vava62600/HexaNode/releases">
    <img src="https://img.shields.io/github/v/release/vava62600/HexaNode?style=for-the-badge" alt="Latest release">
  </a>
  <a href="https://opensource.org/license/mit">
    <img src="https://img.shields.io/badge/license-MIT-darkgreen.svg?style=for-the-badge" alt="Licence">
  </a>
  <a href="https://github.com/vava62600/HexaNode/releases">
    <img src="https://img.shields.io/badge/languages-HTML%20%7C%20PHP%20%7C%20CSS%20%7C%20JS-orange?style=for-the-badge" alt="Languages">
  </a>
</p>

---

## 🧠 À propos du projet

**HexaNode** est un système d’exploitation modulaire web, conçu pour serveurs, combinant les fonctionnalités de Proxmox, TrueNAS Core et Docker en une plateforme unifiée, open-source, moderne et facile d’utilisation.

Il permet de gérer :
- Machines virtuelles (QEMU/KVM),
- Conteneurs Docker,
- Stockage (ZFS, EXT4, NTFS, disques USB, RAID),
- Services réseau (reverse proxy, firewall, VLAN),
- Domotique (Home Assistant et autres),
- Services système et utilisateurs,
- Déploiement d’applications via un AppStore web.

HexaNode s’adresse aux passionnés, makers, développeurs et administrateurs système souhaitant **un contrôle maximal avec une interface moderne**.

---

## 🌍 Langues supportées

- 🇫🇷 Français  
- 🇬🇧 Anglais  
_(d’autres langues peuvent être ajoutées facilement via des modules de traduction)_

---

## 🔧 Technologies & librairies utilisées

| Catégorie              | Outils / Librairies / Services                       |
|------------------------|----------------------------------------------------|
| **Stack Web**          | HTML, CSS, JavaScript, PHP                          |
| **Frontend Framework** | VanillaJS + Loader SPA personnalisé + Router dynamique |
| **UI**                 | Moteur de thèmes custom (light/dark/thèmes)        |
| **Système Auth**       | Authentification par tokens, Fingerprinting IP/Navigateur |
| **Hyperviseur**        | QEMU, KVM, Libvirt, VirtIO                          |
| **Conteneurs**         | Docker, LXC, Podman (optionnel)                     |
| **Stockage**           | ZFS, EXT4, NTFS, Btrfs, mdadm (RAID), USB          |
| **Réseau**             | Apache2, Reverse Proxy (mod_proxy), ufw/iptables   |
| **Automatisation**     | Home Assistant Core, MQTT                           |
| **Services système**   | systemd, cron, rsyslog, SSH, Avahi, SMB, NFS, RSync, FTP, LDAP, ... |
| **Affichage VM**       | Support WebSocket pour prévisualisation live VM    |
| **Packaging**          | ZIP, JSON pour export/import VM et conteneurs      |
| **Applications incluses** | Nextcloud, Syncthing, Pi-Hole, ...               |

---

## 💡 Fonctionnalités clés

- Interface web dynamique en temps réel (SPA)  
- Pas de rechargement de page, intégration API complète  
- Reverse proxy intégré par application (`/appname`)  
- Snapshot VM, partage, import/export (avec méta + disque)  
- Système de plugins et thèmes personnalisables  
- Système complet de logs et alertes  
- Connexion sécurisée avec détection IP et navigateur  
- Renouvellement automatique des tokens + détection d’intrusion  

---

## 🔓 Licence

HexaNode est distribué sous la **licence MIT** — vous êtes libre de l’utiliser, modifier et distribuer, même commercialement.  
Voir le fichier [LICENSE](./LICENSE) pour plus d’informations.

---

## ⭐ GitHub Stars

Si tu apprécies le projet, n’oublie pas de lui donner une **étoile** — cela améliore la visibilité et montre ton soutien à la communauté.

---
