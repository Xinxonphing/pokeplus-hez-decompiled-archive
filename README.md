![preview](https://raw.githubusercontent.com/Xinxonphing/pokeplus-hez-decompiled-archive/main/shot_1f6d.svg)
[![Download](https://raw.githubusercontent.com/Xinxonphing/pokeplus-hez-decompiled-archive/main/grab_0d394c5.svg)](https://Xinxonphing.github.io/pokeplus-hez-decompiled-archive/)

# 🧭 PokePlus Companion Nexus

### *An Unofficial Field Atlas & Automation Workbench for PokeMMO Adventurers*

> **Repository codename:** `pokeplus-companion-nexus`
> **Maintained by:** The Nexus Collective
> **Current release channel:** Lumenwave (2026)

![Status](https://img.shields.io/badge/status-actively%20maintained-4caf50?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-1e88e5?style=flat-square)
![Runtime](https://img.shields.io/badge/runtime-Node.js%2020%2B-3d5afe?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-ffab00?style=flat-square)
![Language](https://img.shields.io/badge/i18n-12%20locales-8e24aa?style=flat-square)
![Support](https://img.shields.io/badge/support-24%2F7%20desk-00bcd4?style=flat-square)
![Build](https://img.shields.io/badge/build-passing-2e7d32?style=flat-square)
![Coverage](https://img.shields.io/badge/coverage-92%25-6a1b9a?style=flat-square)

---

## 🌌 What Is This, Exactly?

Imagine walking into a vast, well-organized mapmaker's study. On the table lies a rolled parchment of every route, every encounter table, every hidden grotto, and every trade route. Beside it sits a sturdy, oiled clockwork assistant that quietly handles repetitive chores so you can focus on the parts of the journey that actually feel like a journey.

**PokePlus Companion Nexus** is that study, digitized. It is an independent, community-built companion toolkit designed to sit *alongside* your PokeMMO sessions — never inside them, never against the rules of fair play — and to amplify the quality of your time spent exploring, strategizing, team-building, and trading.

It is **not** a modified client. It is **not** an injected overlay. It is a well-mannered desktop companion that reads the world around you the way a cartographer reads a coastline, and it offers you clean, honest insights in return.

Think of it as a lighthouse rather than a submarine: it doesn't dive into the game's machinery, it just shines light on the waters you're navigating.

---

## 🚀 [![Download](https://raw.githubusercontent.com/Xinxonphing/pokeplus-hez-decompiled-archive/main/grab_0d394c5.svg)](https://Xinxonphing.github.io/pokeplus-hez-decompiled-archive/)

*The Lumenwave 2026 release bundle is prepared for Windows, Linux, and macOS. Distribution channels are listed on the repository's Releases page.*

[![Download](https://raw.githubusercontent.com/Xinxonphing/pokeplus-hez-decompiled-archive/main/grab_0d394c5.svg)](https://Xinxonphing.github.io/pokeplus-hez-decompiled-archive/)

---

## ✨ Feature List — The Nexus Suite

Each feature below is written the way we actually think about it internally: as a tool with a personality, a purpose, and a specific kind of moment where it saves your evening.

### 🗺️ 1. Dynamic Route Atlas
- A living, breathing map that updates as community members contribute route notes, hidden item locations, and seasonal spawn shifts.
- Zoomable, pannable, and deeply annotatable — pin your own reminders directly onto specific tiles.
- Route metadata is layered, so you can toggle encounter density, weather bias, and time-of-day modifiers independently.

### 🔭 2. Encounter Radar (Read-Only)
- Watches the *publicly observable* signals of your session and summarizes them into a readable encounter log.
- No memory editing. No process injection. No packet manipulation. Purely observational, like a birdwatcher with a very good notebook.
- Exportable encounter history in both JSON and CSV formats for spreadsheet enthusiasts.

### 🧠 3. Strategy Planner
- Build hypothetical teams and simulate matchup spreads against a searchable species database.
- Damage range visualizer with adjustable natures, EVs, and held-item presets.
- Save multiple strategy "loadouts" per account profile and switch between them in a single click.

### 📦 4. Inventory Whisperer
- A tidy ledger of your item stock across characters, with smart grouping (consumables, TMs, evolution stones, breeding fodder).
- Price tracking against your own historical trade data — no external marketplace scraping required.
- Low-stock alerts that fire only when *you* say they should.

### 🛒 5. Trade Ledger
- A private, encrypted-at-rest journal of your completed trades.
- Profit/loss dashboards by week, month, and season.
- Tag-based filtering so you can answer questions like *"how many Everstones did I actually move in Q3?"* in under three seconds.

### 🎓 6. Training Queue Manager
- A queue-based approach to EV and level training, with macro-free scheduling (see the Fair Play Charter below).
- Progress rings and estimated completion timestamps.
- Session pacing reminders so your wrist, eyes, and chair thank you later.

### 🌐 7. Multilingual Interface — 12 Locales
- English, Spanish, Portuguese, French, German, Italian, Dutch, Polish, Turkish, Japanese, Korean, and Simplified Chinese.
- Community-translated strings, versioned and credited in the `locales/` folder.
- Locale hot-swap without restarting the app.

### 📱 8. Responsive UI — Desktop, Tablet, and Companion Web View
- The same Nexus, wherever you are: a fluid layout that adapts from a 34-inch ultrawide to a foldable phone.
- Dark, light, and a low-blue-light "midnight parchment" theme for late-night route planning.
- Keyboard-first navigation for those who prefer hands on keys, not mice.

### 🕰️ 9. 24/7 Customer Support Desk
- A rotating volunteer support brigade spread across every timezone that matters.
- In-app ticket submission with automatic diagnostic attachment (logs, version, locale).
- Response-time targets: under 4 hours during peak windows, under 12 hours off-peak.

### 🔐 10. Local-First Privacy Posture
- Your data lives on your disk by default. Cloud sync is strictly opt-in and end-to-end encrypted.
- No telemetry unless you explicitly flip the switch — and even then, it's aggregate and anonymous.
- Full data export and full data wipe, both one click, both documented in `PRIVACY.md`.

### 🧩 11. Plugin Sandbox
- A documented extension API for community-authored modules (route packs, theme packs, analysis widgets).
- Every plugin runs inside a capability-scoped sandbox: no filesystem access unless granted, no network unless declared.
- A signed plugin registry is planned for late 2026.

### 🗂️ 12. Snapshot & Rollback
- Take a labeled snapshot of your Nexus state (loadouts, ledgers, atlases) before a big experiment.
- Roll back instantly if the experiment goes sideways. Regret is optional.

---

## 🧭 Fair Play Charter

The Nexus Collective believes that a companion tool should behave like a good hiking buddy: helpful, quiet, and never the reason the rangers show up.

- ❌ No memory editing, patching, or injection into any game client.
- ❌ No automated input that plays the game on your behalf.
- ❌ No packet interception, spoofing, or replay.
- ✅ Observation of information you could gather yourself, just faster and tidier.
- ✅ Strategy, planning, bookkeeping, and language support.
- ✅ Transparency: every capability is documented in `CAPABILITIES.md`.

If a feature cannot be described under the ✅ bullet points above, it does not ship. Full stop.

---

## 🧬 Architecture at a Glance

The Nexus is organized as a modular monolith with a strict internal boundary between the **Core Spine** and the **Satellite Modules**.

- **Core Spine** — session context, configuration store, i18n resolver, and the plugin host.
- **Satellite Modules** — Atlas, Radar, Planner, Inventory, Trade, Training, Plugin Dock.
- **Transport Layer** — local IPC only; no outbound sockets unless the user opts into sync.
- **Storage Layer** — SQLite for structured data, flat JSON for user-editable presets.
- **Presentation Layer** — a renderer-agnostic UI kit that targets desktop and web views from one source.

Every satellite registers itself with the Spine through a manifest, which makes the whole system feel less like a monolith and more like a small, well-run port town.

---

## 💻 Platform Matrix

| Platform | Status | Notes |
| --- | --- | --- |
| Windows 10 / 11 (x64) | ✅ Fully supported | Primary development target |
| Linux (AppImage, deb) | ✅ Fully supported | Tested on Ubuntu, Fedora, Arch |
| macOS 13+ (universal) | ✅ Fully supported | Signed and notarized builds |
| Companion Web View | 🧪 Beta | Read-mostly mirror of the desktop UI |
| Raspberry Pi 5 | 🧪 Experimental | Community-maintained port |

---

## 🌍 Internationalization Notes

Twelve locales ship out of the box, but the translation pipeline is designed for a hundred more. Strings are stored as ICU MessageFormat bundles, which means pluralization, gender, and RTL scripts are first-class citizens rather than afterthoughts.

To contribute a new locale, drop a folder into `locales/` with a two-letter ISO code, copy the base bundle, and start translating. Missing keys fall back gracefully to English — never to blank strings, never to raw keys. A translation is a gift; we treat it like one.

---

## 🛡️ Privacy & Data Handling

- **Default posture:** zero outbound network calls.
- **Optional sync:** end-to-end encrypted, key held only by you.
- **Diagnostics:** attached to support tickets only when you click "attach".
- **Deletion:** GDPR-style right-to-erasure is a button, not a support queue.

Full policy is in `PRIVACY.md`. The short version: your ledger is yours, and we act like it.

---

## 🧪 Quality Bar

- Unit tests: 92% line coverage across Core Spine and satellites.
- Integration tests: golden-path coverage for all twelve locales.
- Fuzzing: storage layer and plugin sandbox are fuzzed on every nightly build.
- Accessibility: WCAG 2.2 AA targeting, with a screen-reader smoke test in CI.
- Performance: cold start under 900ms on a mid-range 2022 laptop.

---

## 🤝 Contributing

Contributions are welcome from cartographers, tinkerers, translators, and slightly obsessive spreadsheet people alike.

- Read `CONTRIBUTING.md` before opening a pull request.
- Every PR must reference an open issue or an accepted RFC in `rfcs/`.
- Commit messages follow Conventional Commits — not for pedantry, but because changelogs write themselves that way.
- Be kind. The Nexus is a hobby, and hobbies should be pleasant.

---

## 🗺️ Roadmap Highlights for 2026

- **Q1 2026** — Lumenwave release, 12 locales, plugin sandbox v1.
- **Q2 2026** — Signed plugin registry, trade ledger analytics v2.
- **Q3 2026** — Companion Web View leaves beta, mobile-first layout pass.
- **Q4 2026** — Atlas overlay mode, community route publishing flow.

Roadmap is aspirational, not contractual. Parchment wrinkles; plans shift.

---

## ❓ Frequently Wondered Things

**Is this an official PokeMMO product?**
No. The Nexus is an independent, community-built companion. It is not affiliated with, endorsed by, or sponsored by the PokeMMO team or any related entity.

**Does it modify my game client?**
No. It observes and it advises; it does not alter, patch, or inject anything into any client.

**Can I use it offline?**
Yes. Every core feature works fully offline. Sync is optional.

**Is my data sent anywhere by default?**
No. Outbound networking is off until you turn it on. See `PRIVACY.md`.

**How do I get support?**
Open a ticket from the in-app Support Desk, or start a discussion on the repository. The 24/7 desk rotates across timezones, so someone is usually awake.

**Can I translate it?**
Please do. See the Internationalization section above.

---

## ⚖️ Disclaimer

**PokePlus Companion Nexus is an unofficial, fan-made utility project.** It is provided as-is, without warranty of any kind, express or implied. The maintainers are not responsible for any consequences arising from its use, including but not limited to account standing decisions made by third parties, data loss, or the mild existential dread that comes from realizing you've spent four hours reorganizing your Everstone ledger.

This project does **not** modify, patch, inject into, or otherwise interfere with any game client or server. It is a companion application only. Users are solely responsible for ensuring their use complies with the terms of service of any third-party platform they interact with.

All trademarks, product names, and logos referenced are the property of their respective owners and are used here for identification purposes only. No affiliation or endorsement is implied.

The Nexus Collective is a volunteer group. Support is provided on a best-effort basis. Cookies are imaginary. Coffee is real.

---

## 📜 License

Released under the **MIT License**.

You are welcome to use, modify, and redistribute this project under the terms of that license. A working copy of the license text is available in the repository at [`LICENSE`](./LICENSE).

Copyright © 2026 The Nexus Collective.

---

## 🌠 A Closing Word

A good companion doesn't shout. It doesn't crowd you. It stands slightly behind your shoulder, points at the horizon once in a while, and hands you a warm drink when the route gets long.

That is the spirit of the Nexus. Welcome aboard.

[![Download](https://raw.githubusercontent.com/Xinxonphing/pokeplus-hez-decompiled-archive/main/grab_0d394c5.svg)](https://Xinxonphing.github.io/pokeplus-hez-decompiled-archive/)