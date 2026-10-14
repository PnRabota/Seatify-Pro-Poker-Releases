# Seatify Pro Poker

> **Poker. Optimized.** — Native multi-tabling manager for Windows: automatic
> table placement, hotkeys, table detection, app slots, and rich overlays.
> Built in Rust (Tauri 2) for maximum performance.

**Latest version: `0.19.6`** · Windows 10/11 64-bit

This repository hosts the official Windows installers for Seatify Pro Poker.
The application source lives in a separate repository.

---

## Download & Install

1. Go to the **[latest release](https://github.com/PnRabota/Seatify-Pro-Poker-Releases/releases/latest)** and download the `.exe` installer.
   - Direct link: **[Seatify.Pro.Poker_0.19.6_x64-setup.exe](https://github.com/PnRabota/Seatify-Pro-Poker-Releases/releases/download/v0.19.6/Seatify.Pro.Poker_0.19.6_x64-setup.exe)**
2. Run the installer.
3. Launch Seatify — the setup wizard guides you through rooms, layout, and hotkeys on first start.

> **Windows SmartScreen note:** as a young app, Windows may show a
> "Windows protected your PC" prompt on first run. Click **More info -> Run anyway**.
> This disappears as the app builds reputation. The installer is the exact
> artifact published here.

Updates are automatic: Seatify checks at startup and hourly, and installs
updates without interrupting your session — you normally only download the
installer once.

---

## Features

### Table Management
- **Automatic placement** — your tables are tiled to your layout as they open; drag & drop to rearrange, automatic slot swapping. Ultrawide and multi-monitor friendly.
- **Layout editor + one-click generator** — design layouts on your desktop or generate an optimal one instantly.
- **Auto-switch layouts** — the layout follows your table count automatically.
- **App slots** — dock Windows apps (Discord, browser, tracker...) into slots beside your tables.
- **Pin a table** — exclude a table from auto-tiling so you can resize it or make it full screen freely; it stays put. Accessible from the Table Manager, a hotkey (`Ctrl+Shift+P`), or the tray menu.
- **Table Manager + multi-monitor minimap** — see every detected poker window, grouped by type, with 1-click detection classification and community rule learning.

### Overlays
- **Focus Aura** — a glow around the active table with 3 display modes:
  - *Continuous Aura*: 11 animated effects (Static, Breathing, Pulsating + 8 premium styles).
  - *Focus Blink / Flash*: a brief ~300 ms flash when switching tables, then 0% CPU at rest.
  - *Static Border*: an ultra-crisp 1–2 px border with zero continuous blur cost.
- **Screenshot & Instant Replay (Clips MP4)**:
  - **1-Click Screenshots** — floating capture button per table (`Ctrl+Shift+C`) or fullscreen (`Ctrl+Shift+F`).
  - **Instant Replay (Clips MP4)** — save the last 15s to 2 minutes of table action as an MP4 (H.264) video clip with a subtle *"powered by Seatifypro.com"* watermark. Triggered by turning the overlay button to REC (mouse wheel) or with a global hotkey (`Ctrl+Shift+R`).
  - **Unified Storage** — organized by default in `Pictures/Seatify/Screenshots` and `Pictures/Seatify/Clips`, fully customizable.
  - **8 visual styles** (Minimal, Glass, Neon, Pill, HUD, Solid, Outline, Split) × **5 sizes** (XS to XL).
- **RNG overlay** — an auto-drawn 1–100 number, green/red against a customizable threshold to execute mixed GTO strategies. Features an ultra-compact footprint across all 5 sizes.
- **Card Cover** — a colored rectangle over the board to hide the flop/turn/river, with a one-click opacity toggle or shortcut (`Ctrl+B`) to reveal it (e.g. on an all-in).
- **Session Tracker** — a floating always-on-top timer with table counters and pause/reset controls.
- **Lock & Reset overlays** — freeze overlay positions so accidental clicks never move them; 1-click position reset from settings; hardened tracker-aware Z-order keeping overlays pinned to their tables without occlusion.

### Controls, Performance & UX
- **Global hotkeys** — preconfigured and fully customizable shortcuts:
  - `Ctrl + Shift + R`: Save Instant Replay clip (MP4) of focused table
  - `Ctrl + Shift + C`: Screenshot active table
  - `Ctrl + Shift + F`: Fullscreen screenshot
  - `Ctrl + B`: Toggle Card Cover
  - `Ctrl + Shift + P`: Pin / Unpin table from layout
  - `Ctrl + Shift + T`: Toggle Session Tracker
- **Power & Performance Modes** — customize app refresh rate to fit your machine:
  - **Éco (10 FPS)**: minimal CPU and battery usage for laptops (Replay buffer at 5 FPS).
  - **Standard (30 FPS)**: balanced and smooth for regular multi-tabling sessions.
  - **Turbo (60 FPS)**: silky smooth rendering and 25 FPS broadcast-quality replay for high-refresh-rate setups.
- **10 languages** — English, French, Spanish, German, Portuguese, Italian, Russian, Chinese, Japanese, Korean (auto-detected).
- **Themes** — Dark / Light with customizable accent colors; changes apply instantly.
- **System tray** — quick toggles for hotkeys, layout, Focus Aura, overlay locks, and updates.

---

## Supported Rooms

Winamax · PokerStars · GGPoker / Natural8 · Unibet · PMU · 888poker · PartyPoker · iPoker (bet365, Betfair...) · WPN / ACR (America's Cardroom, BetOnline, TigerGaming) · Ignition / Bovada / Bodog · CoinPoker · PPPoker · Betclic Poker · WPT Global / Nexa Poker.

---

## Performance & Resources

Native Rust (Tauri 2) — zero Electron, zero Java, zero .NET.

| Scenario / Profile | RAM | CPU | Description |
|---|---|---|---|
| **App Idle** | ~25–35 MB | < 0.5% | Waiting for tables, zero active workload |
| **Multi-tabling (Eco Mode)** | ~35–50 MB | < 1% | 10 FPS overlays, 5 FPS replay, maximum battery savings |
| **Multi-tabling (Standard Mode)** | ~45–70 MB | < 2% | 30 FPS overlays, optimal balance between smoothness & footprint |
| **Multi-tabling + Instant Replay (Active Buffer)** | ~60–120 MB | < 3% | In-memory compressed JPEG buffer (~15 MB/table), H.264 export |
| **Mode Turbo (High Refresh & Broadcast)** | ~60–130 MB | ~2–4% | 60 FPS overlays, 25 FPS broadcast replay |

> 🌐 **100% local gameplay**: Your hands, screenshots, video clips, and layouts remain strictly local on your PC. Network is only used for license validation at startup and automatic updates.

---

## Requirements

- **Minimum:** Windows 10 64-bit, dual-core 2 GHz, 4 GB RAM, 200 MB disk.
- **Recommended:** Windows 11, quad-core 2.5 GHz+, 8 GB RAM, multi-monitor.

---

## License & Trial

Seatify Pro requires a license. A **30-day free trial** is available — activate it in-app on first launch. Manage your subscription and device from your [Account Portal](https://seatifypro.com/account).

---

## Links

- **Website:** https://seatifypro.com
- **Web Account Portal:** https://seatifypro.com/account
- **All releases:** https://github.com/PnRabota/Seatify-Pro-Poker-Releases/releases
- **Changelog:** https://seatifypro.com/changelog
