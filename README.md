# Striker

A clean, minimal bowling score calculator for the browser.

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

**History**
- Completed games are saved locally and browsable at any time
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

## Stack

Plain HTML, CSS, and JavaScript. No framework, no build step, no dependencies.

## Data & Privacy

All data (game history, current game, theme preference) is stored in your browser's `localStorage`. Nothing is sent to any server.
