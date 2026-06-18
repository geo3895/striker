# Striker

A clean, minimal bowling score calculator for the browser.

## Features

- **Accurate scoring** — strikes, spares, and 10th frame bonus rolls handled correctly
- **Unlimited players** — add as many players as needed with editable names
- **Three game modes**
  - *By Frame* — each player completes their frame before the next player goes
  - *By Roll* — players rotate after every single roll
  - *Pro / Two Lane* — 2 frames per turn, mirroring tournament-style two-lane play
- **Editable cells** — tap any frame to correct a roll at any time
- **Game history** — completed games are saved locally and can be browsed, reviewed, and deleted
- **Persistent current game** — refreshing the page never loses your progress
- **Dark and light mode** — preference is remembered between sessions
- **How to score guide** — built-in explanation of bowling scoring rules
- **Local clock** — live time and date adjusted to the user's device timezone

## Stack

Plain HTML, CSS, and JavaScript. No framework, no build step, no dependencies.

## Data & Privacy

All data (game history, current game, theme preference) is stored in your browser's `localStorage`. Nothing is sent to any server.
