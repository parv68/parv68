# Building Local-First Infrastructure for Developers
Creator of DevBoxOS, VaultSync, Aegis, and StegaShare.
Focused on Rust, Go, TypeScript, and production-grade developer tooling.
## Systems Engineer & Full Stack Developer

I build **production-grade open-source infrastructure** — embedded runtimes, sync engines, authorization systems, and developer tools — mostly in **Rust**, **Go**, and **TypeScript**. When I'm not designing systems, I'm building full-stack web apps with the MERN stack.

---

## 🚀 Skills & Technologies

### Systems & Infrastructure
![Rust](https://skillicons.dev/icons?i=rust)
![Go](https://skillicons.dev/icons?i=go)
![WebAssembly](https://skillicons.dev/icons?i=wasm)
![Docker](https://skillicons.dev/icons?i=docker)
![PostgreSQL](https://skillicons.dev/icons?i=postgresql)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)

### Full Stack Web
![TypeScript](https://skillicons.dev/icons?i=ts)
![React](https://skillicons.dev/icons?i=react)
![Node.js](https://skillicons.dev/icons?i=nodejs)
![Express](https://skillicons.dev/icons?i=express)
![MongoDB](https://skillicons.dev/icons?i=mongodb)
![TailwindCSS](https://skillicons.dev/icons?i=tailwind)
![Next.js](https://skillicons.dev/icons?i=nextjs)

### Tools & Platforms
![Git](https://skillicons.dev/icons?i=git)
![GitHub](https://skillicons.dev/icons?i=github)
![AWS](https://skillicons.dev/icons?i=aws)
![Linux](https://skillicons.dev/icons?i=linux)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white)

---

## 🏗️ Open Source Projects


### 🌌 [DevBoxOS](https://github.com/parv68/DevBoxOS) — Universal Development Sandbox
> *Spin up fully configured, reproducible development environments with a single command.*

A local-first dev environment manager. Define your entire stack in `devbox.yml`, run `devbox start`, and everything is wired up — dependency resolution, health checks, hot reload, snapshots, and encrypted secrets.

- **Go + gRPC** architecture: CLI ↔ Engine daemon ↔ Docker API
- Auto-detects Node, Go, Rust, Python, Java, Ruby, PHP, PostgreSQL, MySQL, Redis, MongoDB
- **Encrypted secrets** via `age` (X25519 + ChaCha20-Poly1305)
- **Snapshots**: save, export, import, and restore full environment state
- Docker Compose import/export, CI workflow generation, real-time resource monitoring
- 16 releases shipped; cross-platform (Windows, macOS, Linux)

`Go` `Docker` `gRPC` `DevTools` `CLI` `Infrastructure`

---

### 🌌 [VaultSync](https://github.com/parv68/VaultSync) — Local-First Sync Runtime with E2EE
> *Conflict-free, end-to-end encrypted, infrastructure-agnostic synchronization for the local-first era.*

An embedded sync engine that makes apps work **instantly offline**, sync automatically when online, and feel **0ms fast** — because every read/write hits a local database, never a server.

- **CRDT-native** (Yrs): LWW-Register, PN-Counter, OR-Set, rich text — conflicts are impossible
- **Zero-trust E2EE**: coordinator never sees plaintext; X25519 + ChaCha20-Poly1305 encryption
- **Multi-tab safety**: leader election via `BroadcastChannel` + `navigator.locks`, heartbeat crash recovery
- **Infrastructure-agnostic**: Coordinator is a Rust trait — plug in Postgres, Redis, Cloudflare DO, or your own
- React hooks (`useQuery`, `useSyncStatus`), OpenTelemetry, Prometheus metrics

`Rust` `WASM` `TypeScript` `CRDTs` `Local-First` `E2EE` `Offline-First`

---

### 🔐 [Aegis](https://github.com/parv68/AEGIS) — Embedded ReBAC Authorization Runtime
> *Authorization should feel like a library, not infrastructure.*

An embedded, relationship-based authorization (ReBAC) engine inspired by Google Zanzibar and SpiceDB — but built to run **inside your application process** with zero separate infrastructure. Think SQLite, but for permissions.

- **Rust core** with NAPI (Node.js), PyO3 (Python), and CGo (Go) bindings
- Recursive graph traversal with cycle detection and parallel sibling evaluation
- YAML-defined permission schemas with hot-reload and version tracking
- Revision-based snapshot isolation — every mutation produces a monotonic revision token
- SQLite (WAL), PostgreSQL, MySQL, and RocksDB storage backends
- Full audit trail, explain API, GDPR compliance, multi-tenancy

`Rust` `TypeScript` `Go` `Python` `ReBAC` `Authorization` `Embedded Systems`


---

### 🔒 [StegaShare](https://github.com/parv68/StegaShare) — Professional Steganography Tool
> *Hide any file inside an ordinary image — entirely on your device.*

A cross-platform steganography app that hides any file (PDF, ZIP, DOCX) inside a carrier image using AES-256-GCM encryption and LSB pixel manipulation. Runs in the browser, on desktop, and on mobile.

- **Rust core** (`stega-core`) with WASM bridge for browser and Tauri IPC for desktop
- AES-256-GCM + PBKDF2-SHA256 (200,000 iterations, random 96-bit salt + IV)
- LSB pixel steganography: 1 bit per RGB channel per pixel
- Zero-knowledge: all operations run locally, no network calls ever
- Next.js 16 + React 19 frontend with Zustand state; Android/iOS via Tauri v2

`Rust` `WebAssembly` `Next.js` `Tauri` `Cryptography` `Security`

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=parv68&show_icons=true&theme=tokyonight)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=parv68&layout=compact&theme=tokyonight&langs_count=8)

![GitHub Contributions Graph](https://github-readme-activity-graph.vercel.app/graph?username=parv68&theme=react-dark&hide_border=true&area=true)
![GitHub Streak Stats](https://streak-stats.demolab.com?user=parv68&theme=radical&hide_border=true)
![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=parv68&theme=algolia)

## ⏳ WakaTime Stats
![Commits per Day](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=parv68&theme=radical)

---

## 📫 How to reach me

[![Email](https://img.shields.io/badge/-Email-D14836?style=flat&logo=Gmail&logoColor=white)](mailto:parvruhil68@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/parv-ruhil-429659290/)

**Portfolio**: [parv68.github.io/Portfolio](https://parv68.github.io/Portfolio/)
