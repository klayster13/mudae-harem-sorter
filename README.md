# Mudae Harem Sorter

A clean and fast web tool for organizing your **Mudae** waifu/husbando harem. Supports notes and uses your set images!

Drag and drop to reorder, lock your favorites at the top, search by character or series, and instantly generate ready-to-paste `$sm` and `$smpos` commands for Discord.

<img width="2548" height="1305" alt="image" src="https://github.com/user-attachments/assets/c46a5e7e-201c-42c0-97e3-76e1aee64d24" />


## ✨ Features

- **Modern monochrome UI** with elegant #57bb8a accents
- **Drag & drop reordering** with a locked section at the top
- **Per-card controls**: Move Up, Move Down, Series group move, Lock/Unlock
- **Smart Search** — works for both character names and series (supports partial matches)
- **Multiple sorting options**: Name, Series (with kakera tiebreaker), Kakera value
- **Shuffle Unlocked** characters
- **Notes support** — parses and displays Mudae notes (`| s5`, `| s2`, etc.) cleanly
- **Position counter** on every card (X/Y)
- **Navigation sidebar** with "Return to Last Position"
- **Multi-box command generation** — automatically splits long lists with proper `$smpos` chaining
- **Fully responsive** and mobile-friendly
- **Help modal** with complete instructions

## 🚀 Live Version

**[Open Mudae Harem Sorter]([https://yourusername.github.io/mudae-harem-sorter](https://klayster13.github.io/mudae-harem-sorter/))**  

## 📥 How to Use

1. In Mudae Discord, run one of these commands:
   - `$mmak-i-s` → for base kakera values
   - `$mmaki-s` → for key kakera values
2. Copy the entire export output
3. Paste it into the **Import Harem** box and click Import
4. Drag, sort, lock, and organize your harem
5. Click **Generate $sm** to get ready-to-paste commands

## 📋 Changelog

### v1.0 (April 2026)
- Initial public release
- Clean monochrome dark theme with #57bb8a accent color
- Robust import parser supporting notes (`| sX`)
- Drag & drop with locked section at the top
- Per-card controls (↑ ↓ SERIES LOCK)
- Search by character name or series
- Sort by Name / Series / Kakera + Shuffle Unlocked
- Navigation sidebars with "Return to Last Position"
- Multi-box `$sm` / `$smpos` command generation (under 1985 char limit)
- Full in-app help instructions
- Position counters (X/Y) on every card

## 🛠️ Future Plans
We will continue adding features and improvements. Each new version will include an updated changelog here.

## 📝 Notes for Contributors / Forkers
- The app is a single `index.html` file (no build step required)
- All changes should be committed with clear version bumps and changelog entries
- Feel free to fork and customize!

---

Made with ❤️ for the Mudae community.

If you enjoy this tool, feel free to star the repository ⭐
