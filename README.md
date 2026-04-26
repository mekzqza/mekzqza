# Hi, I'm Mek 👋 &nbsp;·&nbsp; TH

**Computer Engineering Student**

```
🎮  Game Backend Engineer   ·   🛠️  DevOps Practitioner   ·   🇹🇭  Thailand
```

> Designing the systems *behind* the game — networking, economy, infra, and everything players never see.

---

## ⚙️ What I Actually Do

### 🎮 Game Backend
Building production-ready backend systems for Roblox games — not just scripts, but real architecture.

- **Networking** — Custom client↔server bridge using [Zap](https://github.com/red-blox/zap) (typed, compiled, zero-overhead)
- **Economy & Inventory** — UUID-based item system, stack management, slot validation, DataStore migration versioning
- **Combat Systems** — Hitbox detection, attack validation pipeline, anti-cheat request flow (`INPUT → Hitbox → C2S → Server validate`)
- **Event Architecture** — Signal-based EventBus with scoped naming (`C2S_`, `S2C_`, `LOCAL_`)

### 🛠️ DevOps / Self-Hosted Infra
Running a real VPS in production, not just localhost.

- **Stack**: Nginx (reverse proxy) · Express · PocketBase · Redis · Next.js — all containerized with Docker Compose
- **CI/CD**: GitHub Actions pipelines for automated deploy
- **Networking**: UFW firewall hardening, Docker internal networking, Cloudflare Tunnel
- **Platform**: DigitalOcean Droplet (self-managed, no PaaS magic)

---

## 🧰 Tech Stack

| Layer | Tools |
|---|---|
| **Game Engine** | Luau (Strict Mode), Roblox Studio, Rojo, Wally, Zap, Aftman |
| **Game Backend** | EventBus, ServerNetworkHandler, InventoryService, PlayerData migration |
| **Backend / API** | Node.js, Express.js, PocketBase, Redis |
| **Frontend** | Next.js, React, TypeScript |
| **DevOps** | Docker, Docker Compose, Nginx, GitHub Actions, UFW |
| **Platform** | DigitalOcean, Cloudflare |
| **Hardware** | ESP32, Arduino (FreeRTOS, WebSocket) |

---

## 🏗️ Architecture I've Built

```
┌─────────────────────────────────────────────────────┐
│                  OneShotArena Stack                  │
├───────────────────────┬─────────────────────────────┤
│    Roblox Client      │       VPS (DigitalOcean)     │
│  ─────────────────    │  ────────────────────────    │
│  CombatHandler        │  Nginx (reverse proxy)       │
│  InventoryService     │  Express API                 │
│  EventBus (Signal)    │  PocketBase (DB + Auth)      │
│  Zap (networking)     │  Redis (cache/sessions)      │
│  Rojo (sync)          │  Docker Compose              │
└───────────────────────┴─────────────────────────────┘
```

---

## 📌 Featured Projects

| Project | What it is | Stack |
|---|---|---|
| [OneShotArena-Roblox](https://github.com/mekzqza/OneShotArena-Roblox) | Arena game — combat, inventory & networking systems | Luau, Zap, Rojo |
| [OneShotArena-BackEnd-VPS](https://github.com/mekzqza/OneShotArena-BackEnd-VPS) | Self-hosted game backend infra | Docker, Nginx, Express, PocketBase, Redis |
| [Ai-WebChat](https://github.com/mekzqza/Ai-WebChat) | AI-powered web chat app | TypeScript, Next.js |
| [Smart-Gate-LPR-System](https://github.com/mekzqza/Smart-Gate-LPR-System) | Smart gate with license plate recognition | TypeScript, ESP32 |

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mekzqza&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="160" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mekzqza&layout=compact&theme=tokyonight&hide_border=true" height="160" />
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=mekzqza&color=00bfff&style=flat-square&label=profile+views" />
</p>
