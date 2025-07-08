**Dev Environment – WSL2 + Docker**

Environment focused on developers who need an isolated setup outside their main workflow. Ideal for local development with Docker and WSL2.

---

**Features**
- WSL2 on Windows
- Docker-based environment
- NGINX reverse proxy
- Modular and extensible (Node.js, PHP, Python, etc.)

---

**Includes**
- Ubuntu via WSL2
- Docker & Docker Compose
- Basic folder structure for code and config

---

**Install (manual steps for now)**

1. Enable WSL2 on Windows  
2. Install Ubuntu from Microsoft Store  
3. Install Docker Desktop with WSL2 integration

---

**Usage (once configured)**

```bash
docker compose up -d
