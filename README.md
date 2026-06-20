# 🎳 Striker

> A clean, minimal bowling score calculator for the browser — installable as a PWA.

---

## Features

### 🎯 Scoring
- Accurate **strike**, **spare**, and **10th frame** bonus roll calculation
- Running cumulative score per frame
- **Max possible score** tracker — updates after every roll

### 👥 Players
- **Unlimited players** with editable names
- Per-player color coding

### ⚙️ Game Settings

| Setting | Options |
|---|---|
| **Game Mode** | Normal *(10 frames)* · Unlimited *(endless frames)* |
| **Turn Order** | By Frame · By Roll · Pro / Two Lane |

### ✏️ Editing
- Tap any frame cell to correct a roll at any time
- Undo last roll from within the frame popup

### 🏆 End of Game
- Summary screen with **winner announcement** and players ranked by score
- Save, skip, or keep reviewing options

### 📋 History
- Completed games saved locally and browsable at any time
- Full **scoreboard replay** for any saved game
- Delete individual entries

### 💾 Persistence
- Current game state **survives page refreshes**
- Theme preference remembered between sessions

### 🌙 Other
- Built-in scoring rules guide
- **Dark and light mode**
- Live clock adjusted to the user's device timezone
- **PWA** — works offline, installable from browser to home screen

---

## Stack

> Plain HTML, CSS, and JavaScript. No framework, no build step, no dependencies.

---

## Data & Privacy

All data — game history, current game state, and theme preference — is stored in your **browser's `localStorage`**. Nothing is sent to any server.
