# Hi, I'm Benedikt 👋

**Software Engineer** from Germany, building tools that bridge AI agents with real systems.

## 🚀 Current Project: OpenClaw Windows Agent

A native Windows application that connects your PC to an [OpenClaw](https://openclaw.ai) Gateway, enabling AI agents to interact with your Windows machine.

[![.NET](https://img.shields.io/badge/.NET-8.0-512BD4?style=flat-square&logo=dotnet)](https://dotnet.microsoft.com/)
[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=flat-square&logo=windows)](https://www.microsoft.com/windows)
[![Status](https://img.shields.io/badge/Status-Alpha-orange?style=flat-square)](https://github.com/BenediktSchackenberg/openclaw-windows-agent)

### What It Does

```
┌─────────────────────────────────────────────────────────────────┐
│                     YOUR NETWORK                                 │
│                                                                  │
│  ┌──────────────┐         WebSocket          ┌───────────────┐  │
│  │   Linux PC   │ ◄──────────────────────►   │  Windows PC   │  │
│  │              │                            │               │  │
│  │  OpenClaw    │    "Run notepad.exe"       │  Agent GUI    │  │
│  │  Gateway     │ ─────────────────────────► │      +        │  │
│  │              │                            │  Background   │  │
│  │  (AI Agent)  │ ◄───────────────────────── │  Service      │  │
│  │              │     { "pid": 1234 }        │               │  │
│  └──────────────┘                            └───────────────┘  │
└─────────────────────────────────────────────────────────────────┘
```

### ✨ Features

- 🔗 **Remote Command Execution** — Run PowerShell/CMD from AI agents
- 📊 **Hardware Inventory** — CPU, RAM, GPU, disks, mainboard info
- 🛡️ **Security Scanning** — Firewall, Defender, TPM, SecureBoot status
- 🌐 **Network Monitoring** — Open ports, connections, interfaces
- 🖥️ **Software Inventory** — Installed apps, services, browser extensions
- ⚙️ **Windows Service** — Runs 24/7, survives reboots
- 🎨 **Dark Theme UI** — Slick WPF interface with live logs

### 📦 Check It Out

**→ [BenediktSchackenberg/openclaw-windows-agent](https://github.com/BenediktSchackenberg/openclaw-windows-agent)**

---

## 🔧 Tech Stack

- **Languages:** C#, PowerShell, Python, TypeScript
- **Frameworks:** .NET 8, WPF, FastAPI
- **Databases:** PostgreSQL, TimescaleDB, SQL Server
- **AI/Agents:** OpenClaw, Claude, GPT-4o
- **Tools:** Visual Studio, Git, Docker

## 📫 Contact

- 🌐 [schackenberg.com](https://schackenberg.com)
- 💼 [GitHub](https://github.com/BenediktSchackenberg)
