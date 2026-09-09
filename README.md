# Seatify Pro Poker

> **Poker. Optimized.** — Native multi-tabling manager for Windows: automatic
> table placement, hotkeys, table detection, app slots, and rich overlays.
> Built in Rust (Tauri 2) for maximum performance.

**Latest version: `0.16.12`** · Windows 10/11 64-bit

This repository hosts the official Windows installers for Seatify Pro Poker.
The application source lives in a separate repository.

---

## Download & Install

1. Go to the **[latest release](https://github.com/PnRabota/Seatify-Pro-Poker-Releases/releases/latest)** and download the `.exe` installer.
   - Direct link: **[Seatify.Pro.Poker_0.16.12_x64-setup.exe](https://github.com/PnRabota/Seatify-Pro-Poker-Releases/releases/download/v0.16.12/Seatify.Pro.Poker_0.16.12_x64-setup.exe)**
2. Run the installer.
3. Launch Seatify — the setup wizard guides you through rooms, layout and hotkeys on first start.

> **Windows SmartScreen note:** as a young app, Windows may show a
> "Windows protected your PC" prompt on first run. Click **More info -> Run anyway**.
> This disappears as the app builds reputation. The installer is the exact
> artifact published here.

Updates are automatic: Seatify checks at startup and hourly, and installs
updates without interrupting your session — you normally only download the
installer once.

---

## Features

### Table management
- **Automatic placement** — your tables are tiled to your layout as they open; drag & drop to rearrange, automatic slot swapping. Ultrawide and multi-monitor friendly.
- **Layout editor + one-click generator** — design layouts on your desktop or generate an optimal one instantly.
- **Auto-switch layouts** — the layout follows your table count automatically.
- **App slots** — dock Windows apps (Discord, browser, tracker...) into slots beside your tables.
- **Pin a table** — exclude a table from auto-tiling so you can resize it or make it full screen freely; it stays put. From the Table Manager, a hotkey (Ctrl+Shift+P), or the tray menu.
- **Table Manager + multi-monitor minimap** — see every detected poker window, grouped by type.

### Overlays
- **Focus Aura** — a glow around the active table (11 effects; configurable color, thickness, corner radius and direction).
- **Screenshot** — one-click floating capture button per table, plus a fullscreen capture.
- **RNG overlay** — an auto-drawn 1-100 number, green/red against a threshold, to play a strategy X% of the time (per-table or a single floating overlay).
- **Card Cover** — a colored rectangle over the board to hide the flop/turn/river, with a one-click opacity toggle to reveal it (e.g. on an all-in).
- **Session Tracker** — a floating always-on-top timer with table and hand counters (3 themes).
- **Lock overlays** — freeze overlay positions so an accidental drag never moves or resizes them; toggled per overlay type from the app or the tray.

### Controls & UX
- **Global hotkeys** — keyboard shortcuts for your poker actions, with per-site sizing profiles.
- **10 languages** — English, French, Spanish, German, Portuguese, Italian, Russian, Chinese, Japanese, Korean (auto-detected).
- **Themes** — Dark / Light with 3 accent colors; every change applies instantly and is saved automatically.
- **System tray** — quick toggles for hotkeys, layout, Focus Aura, overlay locks, updates.

---

## Supported rooms

Winamax · PokerStars · GGPoker / Natural8 · Unibet · PMU · 888poker ·
PartyPoker · iPoker (bet365, Betfair, FanDuel...) · WPN / ACR (America's
Cardroom, BetOnline, TigerGaming) · Ignition / Bovada / Bodog · CoinPoker ·
PPPoker · Betclic Poker · WPT Global / Nexa Poker.

---

## Performance

Native Rust (Tauri 2) — no Electron, no Java, no .NET.

| Scenario | RAM | CPU |
|----------|-----|-----|
| Idle | ~25-30 MB | < 1% |
| Active multi-tabling | ~30-50 MB | < 2% |

**100% offline** in normal use — the network is only used for updates and
license validation.

---

## Requirements

- **Minimum:** Windows 10 64-bit, dual-core 2 GHz, 4 GB RAM, 200 MB disk.
- **Recommended:** Windows 11, quad-core 2.5 GHz+, 8 GB RAM, multi-monitor.

---

## License & trial

Seatify Pro requires a license. A **30-day free trial** is available — activate
it in-app on first launch. Manage your subscription and device from your
account.

---

## Links

- **Website:** https://seatifypro.com
- **All releases:** https://github.com/PnRabota/Seatify-Pro-Poker-Releases/releases
- **Changelog:** https://seatifypro.com/changelog

