# Windows "Take Ownership" Context Menu Utility

A lightweight, automated Windows Registry script to add a **"Take Ownership"** option directly to the right-click context menu for files, folders, and drives. Designed for IT Professionals and SysAdmins to resolve "Access Denied" and "TrustedInstaller" permission locks on Windows Desktop & Windows Server systems.

Packaged & Maintained by **[Erkmenhost Ltd](https://erkmenhost.com)** — UK-registered Enterprise Cloud Infrastructure & Server Solutions Provider.

---

## 📖 Official Technical Guide
For the complete step-by-step breakdown, CMD syntax (`takeown` & `icacls`), and subfolder permission inheritance reset guides, read our official documentation:

👉 **[How to Change Windows File Ownership to Fix 'Access Denied' Errors](https://erkmenhost.com/article/how-to-change-windows-file-ownership-to-fix-access-denied-errors)**

---

## 🚀 Quick Start & Installation

### 1. Enable Context Menu
* Download **`Add_Take_Ownership_to_context_menu_erkmenhost.reg`**.
* Double-click to merge it with your Windows Registry.
* Click **Yes** on the Windows confirmation prompt.
* Right-click any file or folder and select **Take Ownership**.

### 2. Remove Context Menu
* Download **`Remove_Take_Ownership_to_context_menu_erkmenhost.reg`**.
* Double-click to merge it and restore default Windows Context Menu settings.

---

## 🛡️ Security & System Protection
To prevent accidental system corruption, this script includes built-in filters (`AppliesTo`) that intentionally exclude critical OS directories (`C:\Windows`, `C:\Program Files`, `C:\ProgramData`).

---

### 🌐 About Erkmenhost
Erkmenhost Ltd provides high-performance, enterprise-grade cloud solutions hosted in European Data Centers (FR / PL / UK):
* **High-Performance Cloud VPS** (NVMe Storage, 1Gbps Uplink)
* **Dedicated Bare-Metal Servers** (Enterprise Anti-DDoS Mitigation)
* **Domain Registration & SSL Certificates**

Official Website: **[https://erkmenhost.com](https://erkmenhost.com)**
