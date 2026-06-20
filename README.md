# Striker

A clean, minimal bowling score calculator for the browser. Installable as a PWA.

## Features

**Scoring**
- Accurate strike, spare, and 10th frame bonus roll calculation
- Running cumulative score per frame
- Max possible score tracker — updates after every roll

**Players**
- Unlimited players with editable names
- Per-player color coding

**Game Settings**
- *Game Mode* — Normal (10 frames) or Unlimited (endless frames for practice or extended play)
- *Turn Order* — By Frame, By Roll, or Pro / Two Lane (2 frames per turn, tournament style)

**Editing**
- Tap any frame cell to correct a roll
- Undo last roll from within the frame popup

**End of game**
- Game summary screen with winner announcement and players ranked by score
- Save, skip, or keep reviewing options

**History**
- Completed games saved locally and browsable at any time
- Each entry shows game name, date, players, mode, and winner score
- Full scoreboard replay for any saved game
- Delete individual entries

**Persistence**
- Current game state survives page refreshes
- Theme preference remembered between sessions

**Other**
- Built-in scoring rules guide
- Dark and light mode
- Live clock adjusted to the user's device timezone
- Installable as a PWA — works offline, launches from home screen

## Stack

Plain HTML, CSS, and JavaScript. No framework, no build step, no dependencies.

## PWA

The app includes a service worker and web manifest. After the first visit it works fully offline. On Android, Chrome will prompt to install it. On iOS, use Share → Add to Home Screen.

When deploying updates, bump the cache version in `pwa/sw.js` from `striker-v1` to `striker-v2` (and so on) so users receive the latest version.

## Data & Privacy

All data (game history, current game, theme preference) is stored in your browser's `localStorage`. Nothing is sent to any server.
