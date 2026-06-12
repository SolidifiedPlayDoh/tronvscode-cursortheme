# Tron: Legacy — VS Code / Cursor Theme

Neon grid aesthetics from the Grid. A dark theme for [VS Code](https://code.visualstudio.com/) and [Cursor](https://cursor.com/) inspired by *Tron: Legacy*.

## Features

- Pure void-black editor with neon cyan grid accents
- Amber/orange syntax highlights (light cycle energy)
- Layered UI contrast — sidebar, tabs, panel, and status bar each read as distinct zones
- Full workbench coverage: terminal, git, chat, diff, semantic highlighting

## Install

### From VSIX (easiest)

1. Download the latest `.vsix` from [Releases](https://github.com/Solidifiedplaydoh/tronvscode-cursortheme/releases)
2. Open VS Code or Cursor
3. `Cmd+Shift+P` → **Extensions: Install from VSIX...**
4. Select the downloaded file
5. `Cmd+K Cmd+T` → choose **Tron: Legacy**

### From source

```bash
git clone https://github.com/Solidifiedplaydoh/tronvscode-cursortheme.git
cd tronvscode-cursortheme
```

Then in Cursor/VS Code:

- `Cmd+Shift+P` → **Developer: Install Extension from Location...** → select the cloned folder

Or press **F5** in the repo to open an Extension Development Host and preview live.

### Build VSIX yourself

```bash
npx @vscode/vsce package
```

## Palette

| Role | Color |
|------|-------|
| Void background | `#000000` |
| Chrome / sidebar | `#0c1424` |
| Neon cyan | `#00d9ff` |
| Light cycle orange | `#ff9933` |
| CLU fire | `#ff6600` |
| Grid purple | `#a855f7` |
| Derezz red | `#ff3355` |

## License

MIT — see [LICENSE](LICENSE).
