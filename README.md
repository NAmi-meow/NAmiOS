<p align="center">
  <img src="assets/banner.png" alt="NAmiOS banner" width="100%" />
</p>

<h1 align="center">🐾 NAmiOS</h1>
<h3 align="center">A from‑scratch, cross‑platform 64‑bit OS — built by <a href="https://github.com/NAmi-meow">NAmi-meow</a></h3>

<p align="center">
  <img src="https://img.shields.io/badge/status-alpha-orange?style=flat" />
  <img src="https://img.shields.io/badge/architecture-x86__64-blue?style=flat&logo=intel" />
  <img src="https://img.shields.io/badge/platform-cross-red?style=flat" />
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat" />
  <img src="https://img.shields.io/badge/made%20with-%E2%9D%A4%EF%B8%8F%20by%20NAmi--meow-ff69b4?style=flat" />
</p>

---

## 🧠 Philosophy
**NAmiOS** is not a Linux distribution, not a fork, not a remix.  
It is a fully independent 64‑bit operating system written from scratch — with two souls inside it:

- **Naka** engineered the kernel, the drivers, the binary translator, and every low‑level detail.
- **Ami** designed the visual language, the themes, and the seamless app aesthetics.

We believe an OS should be **free, fast, and beautiful** — without compromises.

---

## ⚡ Key Features

### 🌐 Built‑in DPI for a free Internet
The network driver includes a **deep packet inspection (DPI) circumvention engine** directly in the kernel.  
No extra software, no VPNs — your connection is clean by default.

### 🔄 True Cross‑Platform Binary Compatibility
Run apps from **Windows, Linux, macOS, Android and iOS** — without emulators, without virtual machines.  
NAmiOS translates opcodes to native machine code **during installation or first launch**.  
The result: near‑native performance with zero overhead after the first run.

### 🎨 Radical Customisation
- **Wallpapers** – static, video, or interactive **scenes** (like Wallpaper Engine).
- **Widgets** – clocks, system monitors, weather, custom scripts — all themable.
- **Window Managers** – stacking, tiling, dynamic; switch on the fly.
- **Themes** – several built‑in, plus third‑party ones via **.ndip** (NAmiOS Design Install Package).  
  One click, and your whole desktop changes personality.
- **Unified App Design System** – every application automatically follows the current theme.  
  Even foreign apps are visually integrated, thanks to our compositor layer.

### 🧱 Built from Scratch
No Linux kernel, no BSD, no legacy cruft.  
Custom kernel, custom bootloader, custom everything — for maximum control and minimal bloat.

---

## 📸 Screenshots
*(coming soon — Ami is working on the first theme right now 🎨)*

---

## 🛠️ Building NAmiOS
> **Note:** The build system is under active development. Instructions will be published as soon as the first public image is ready.

```bash
git clone https://github.com/NAmi-meow/NAmiOS.git
cd NAmiOS
python3 build.py run
