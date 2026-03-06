# 🗺 Realm Keeper

**A fantasy world-building tool for tabletop RPG dungeon masters.**

Build living, interconnected campaign worlds — draw maps, place pins, write journal entries for NPCs, factions, quests, monsters and more. Link everything together with `[[backlinks]]` and visualise your world as a connection graph.

Made by [Script Work Studio](https://scriptworkstudio.github.io).

---

## ⬇ Download

### Desktop App (Recommended)
No storage limits. Saves directly to your filesystem. Runs fully offline.

👉 **[Download Realm Keeper for Windows](https://github.com/scriptworkstudio/realmkeeper/releases/latest)**

### Lite (Browser Version)
No install needed — runs in Chrome or Edge.

👉 **[Open Realm Keeper Lite](https://scriptworkstudio.github.io/realmkeeper/)**

> The Lite version stores your world in browser localStorage (~5MB limit). Use the 💾 Save button regularly to back up your world as a `.json` file.

---

## ✨ Features

- **Interactive map canvas** — pan, zoom, upload any fantasy map image
- **8 pin types** — City, Dungeon, Wilderness, Landmark, Port, Ruin, Stronghold, Mystery
- **Nested maps** — link a pin to a child map and navigate the hierarchy with breadcrumbs
- **Full wiki system** — NPC, Faction, Quest, Item, Lore, Monster, Location entry types
- **`[[Backlinking]]`** — type `[[` in any field to link to any entry or pin; reverse links shown automatically
- **Connection graph** — visual web of everything in your world, filterable by type
- **Open5e monster search** — import full D&D 5e SRD stat blocks live
- **Auto-save** — desktop app saves continuously; lite version saves to localStorage
- **Save / Load** — export your world as a `.json` file and reload it anytime

---

## 🚀 Getting Started

### Using the Desktop App
1. Download `Realm Keeper Setup 1.0.0.exe` from [Releases](https://github.com/scriptworkstudio/realmkeeper/releases/latest)
2. Run the installer
3. Launch Realm Keeper and click **Try a Demo** to explore, or **＋ Add Map** to start your own world

### Using the Lite Version
1. Open [scriptworkstudio.github.io/realmkeeper](https://scriptworkstudio.github.io/realmkeeper/)
2. Click **Try a Demo** or **＋ Add Map**
3. Use **💾 Save** regularly to back up your world to a file

---

## 📁 Repository Structure

```
realmkeeper/
├── index.html          # Realm Keeper Lite (served via GitHub Pages)
└── README.md           # This file
```

The desktop app source lives in the `realm-keeper-app/` folder and is built with [Electron](https://www.electronjs.org/). The compiled installer is published as a GitHub Release asset — it is not committed to the repo.

---

## 🛠 Building the Desktop App

Requires [Node.js](https://nodejs.org) (LTS).

```bash
cd realm-keeper-app
npm install
npm start        # Run in development
npm run build    # Build Windows installer → dist/
```

---

## ☕ Support

If you find Realm Keeper useful, consider supporting Script Work Studio:

👉 [buymeacoffee.com/scriptworkstudio](https://buymeacoffee.com/scriptworkstudio)

Questions or feedback? [scriptworkstudio@hotmail.com](mailto:scriptworkstudio@hotmail.com)

---

*Realm Keeper is free to use. Built with love for dungeon masters everywhere.*
