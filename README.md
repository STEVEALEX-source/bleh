# WebOS + Piano

A browser desktop environment with apps built in — including a **playable piano**.

Open `index.html` (or serve the folder). No install.

## Apps on the desktop

| App | What it does |
|-----|----------------|
| **Piano** | One-octave keyboard, songs, octave + volume. Keys `A W S E D F T G Y H U J K` |
| **Calculator** | Basic arithmetic |
| **Timer** | 1 / 5 / 10 / 25 min presets |
| **Tasks** | Checklist saved in localStorage |
| **Files / Notepad / Terminal / Browser / Settings** | Original webOS apps |

## Features

- Boot screen, draggable/resizable windows, taskbar, start menu
- Live canvas wallpapers (Aurora, Nebula, Orbs, Circuit)
- Accent colors, optional UI sounds
- Right-click desktop menu
- Everything stays local (localStorage)

## Run

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Or double-click `index.html`.

## Notes

Piano, calc, timer, and tasks are **inside** the OS windows — not separate pages.
