# Mudae Harem Sorter

A clean and fast web tool for organizing your **Mudae** waifu/husbando harem. Supports notes and uses your set images!

Drag and drop to reorder, lock your favorites at the top, search by character or series, and instantly generate ready-to-paste `$sm` and `$smpos` commands for Discord.

<img width="2548" height="1305" alt="image" src="https://github.com/user-attachments/assets/c46a5e7e-201c-42c0-97e3-76e1aee64d24" />

## 🚀 Live Version

**[Open Mudae Harem Sorter]** https://klayster13.github.io/mudae-harem-sorter/

## Features
- Paste Mudae export (`$mmak-i-s` or `$mmaki-s`)
- Drag & drop reordering with locked characters pinned at the top
- Per-card controls (↑ ↓ SERIES Lock/Unlock)
- Bulk move by series
- Multiple sort options (Name, Series, Kakera, Shuffle Unlocked)
- Search by character or series
- Auto-save to browser + manual Save/Load JSON backups
- Generates properly split `$sm` / `$smpos` commands for Discord
- Clean monochrome UI with accent color

## Changelog

### v1.1test (Current)
**Date:** April 2026  
**Changes from v1.0:**
- Added full save system:
  - Automatic localStorage saving after every change (import, drag, lock, sort, etc.)
  - Manual **Save** button with custom filename popup
  - **Load** button supporting both file upload and JSON paste
- Updated top bar layout:
  - Simplified button labels (`Import Harem` → `Import`, `Load Save` → `Load`, `Generate $sm` → `$sm`)
  - Reordered buttons so **Help** is now at the far right
- Replaced monochrome description with clear **v1.1test** version indicator
- Added Content-Security-Policy meta tag to improve external image loading on GitHub Pages
- Expanded Help modal with a new **Save System** section at the top

### v1.0 (Initial Release)
- Core functionality: Import, drag & drop grid, locking, per-card controls, sorting, search, series bulk move, command generation
- Sidebars for navigation and sorting
- Slim top bar and clean monochrome design
- Auto-open help modal on first load

## How to Use
1. Go to your GitHub Pages URL
2. Click **Import** and paste your Mudae export (`$mmak-i-s` or `$mmaki-s`)
3. Drag cards to reorder, use per-card buttons to lock/move
4. Use right sidebar to sort or shuffle
5. Click **$sm** to generate ready-to-paste Discord commands
6. Use **Save** / **Load** to backup or restore your sorted harem

## Local Development
- Download `index.html`
- Open the file directly in your browser (double-click)

## Contributing / Feedback
Feel free to open issues or pull requests on the repository.

---

Made with ❤️ for the Mudae community.

If you enjoy this tool, feel free to star the repository ⭐
