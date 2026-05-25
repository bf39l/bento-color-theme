# Bento Color Theme

The Bento Color Theme is a VS Code theme extension inspired by Monkeytype's `bento` palette.

Source code: `https://github.com/bf39l/bento-color-theme`

## Features

- Bento-inspired workbench and editor colors.
- Token colors for common syntax scopes.
- Integrated terminal ANSI color mapping.

### Current Core Colors

- Editor background: `#2d394d`
- Editor foreground: `#fffaf8`
- Accent (focus/cursor/links): `#ff7a90`
- Surface panels and inputs: `#263041`
- Secondary UI borders and selection tint: `#4a768d`
- Error: `#ee2a3a`

### Integrated Terminal ANSI Mapping

- normal black `#263041`, red `#ee2a3a`, green `#5b879f`, yellow `#ff7a90`
- normal blue `#6d95a9`, magenta `#ff7a90`, cyan `#9ab0bf`, white `#fffaf8`
- bright black `#2d394d`, bright red `#f04040`, bright green `#5b879f`, bright yellow `#ff95a6`
- bright blue `#6d95a9`, bright magenta `#ff9fb0`, bright cyan `#9ab0bf`, bright white `#ffffff`

## Screenshot

![Bento VS Code](https://raw.githubusercontent.com/bf39l/bento-color-theme/main/vscode-bento-theme/doc/screenshots/vscode.png)

## Installation

1. Open Extensions in VS Code.
2. Choose `Install from VSIX...`.
3. Select the packaged `.vsix` for this extension.
4. Run `Preferences: Color Theme` and pick `Bento`.

## Requirements

No additional runtime requirements.

## Extension Settings

This extension contributes a color theme and does not add custom settings.

## Development

1. Open this folder in VS Code.
2. Press `F5` to launch an Extension Development Host.
3. In the new window run `Preferences: Color Theme`.
4. Select `Bento`.

To package locally:

1. Install `vsce`: `npm i -g @vscode/vsce`
2. Run `vsce package --out ./outputs` from this folder.

To publish to the Visual Studio Marketplace:

1. Run `vsce publish` from this folder.

To unpublish from the Visual Studio Marketplace:

1. Run `vsce unpublish bf39LMintysNZ.bento-vscode-theme` from this folder.
2. To skip confirmation, run `vsce unpublish bf39LMintysNZ.bento-vscode-theme --force`.

## Release Notes

See `CHANGELOG.md` for version history.

## License

This extension is licensed under GNU General Public License v3.0 (GPL-3.0). See `LICENSE`.

This work adapts the Monkeytype `bento` palette/theme mapping. Preserve attribution and license notices when redistributing derivative versions.

## Source Inspiration

Base palette inspiration:

- `https://github.com/monkeytypegame/monkeytype.git`
- `/frontend/src/ts/constants/themes.ts`
