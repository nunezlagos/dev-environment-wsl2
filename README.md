# Dev Environment - WSL2 + Docker

A development environment designed for developers who require an isolated setup apart from their main workflow. Supports version control and modular extensions.

---

## 🚀 Features

- WSL2-based environment on Windows
- Docker preconfigured
- NGINX reverse proxy (configurable)
- Ready for multiple tech stacks (Node.js, PHP, Python, etc.)
- Clean separation from your main system
- Easy to reproduce, share, and reset

---

## 📦 Includes

- WSL2 (Ubuntu)
- Docker & Docker Compose
- NGINX
- Preconfigured volumes for code
- Optional mounts and aliases

---

## 🛠️ Setup Instructions

### 1. Prerequisites

- Windows 10/11 with WSL2 enabled
- Virtualization enabled in BIOS
- Admin permissions

### 2. Install WSL2

```powershell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
wsl --set-default-version 2
