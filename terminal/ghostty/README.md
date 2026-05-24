# Bento For Ghostty

This folder contains a Ghostty theme inspired by Monkeytype's `bento` theme.

## Source

The base colors are inspired by Monkeytype's `bento` theme in:

- `https://github.com/monkeytypegame/monkeytype.git`
- `/frontend/src/ts/constants/themes.ts`

## Files

- `Bento`: Ghostty theme file

## Current Values

### Core

- `background`: `#2d394d`
- `foreground`: `#fffaf8`
- `cursor-color`: `#ff7a90`
- `cursor-text`: `#2d394d`
- `selection-background`: `#4a768d`
- `selection-foreground`: `#fffaf8`

### ANSI Palette (`0-15`)

- `0 #263041`, `1 #ee2a3a`, `2 #5b879f`, `3 #ff7a90`
- `4 #6d95a9`, `5 #ff7a90`, `6 #9ab0bf`, `7 #fffaf8`
- `8 #8da3b3`, `9 #f04040`, `10 #5b879f`, `11 #ff95a6`
- `12 #6d95a9`, `13 #ff9fb0`, `14 #9ab0bf`, `15 #ffffff`

### Note

`palette = 8` is intentionally lighter (`#8da3b3`) so shell autosuggestion/hint text is readable and not the same as command input color.

## Screenshot

![Bento Ghostty](../doc/screenshots/ghostty.png)

## Install

1. Create the Ghostty themes directory if needed:
   - `mkdir -p ~/.config/ghostty/themes`
2. Copy `Bento` into `~/.config/ghostty/themes/Bento`.
3. In your Ghostty config, set:
   - `theme = Bento`
4. Reload Ghostty config or restart Ghostty.

You can also reference the file by absolute path with `theme = /absolute/path/to/Bento`.
