# Oni Dusk Themes

Dark themes for VS Code & Cursor — soft pastel dusk base, neon accent variants.

Based on / strongly inspired by [Bearded Theme](https://github.com/BeardedBear/bearded-theme) (Black & Gems) by [BeardedBear](https://github.com/BeardedBear), with a distinct dusk atmosphere and brighter neon accents.

![Oni Dusk Themes preview](./OniThemes.png)

| | |
|---|---|
| **Extension id** | `onivoid.oni-dusk-themes` |
| **Display name** | Oni Dusk Themes |

## Themes

| Theme | Accent |
|-------|--------|
| **Oni Lime** | `#a8ff53` |
| **Oni Blurple** | `#7053ff` |
| **Oni Cyan** | `#53e8ff` |
| **Oni Magenta** | `#ff53c6` |
| **Oni Amber** | `#ffc053` |
| **Oni Coral** | `#ff6b53` |

Shared base: **Oni Dusk** — soft mauve charcoal. Syntax colors stay gem-like across all variants; only the UI accent changes.

## Install

### VS Code (Microsoft Marketplace)

1. Open **Extensions** (`Cmd+Shift+X` / `Ctrl+Shift+X`)
2. Search for **Oni Dusk Themes**
3. Click **Install**
4. Open the theme picker (`Cmd+K Cmd+T` / `Ctrl+K Ctrl+T`) and choose a variant

Direct link: [marketplace.visualstudio.com](https://marketplace.visualstudio.com/items?itemName=onivoid.oni-dusk-themes)

### Cursor (Open VSX)

1. Open **Extensions** (`Cmd+Shift+X` / `Ctrl+Shift+X`)
2. Search for **Oni Dusk Themes**
3. Click **Install**
4. Open the theme picker (`Cmd+K Cmd+T` / `Ctrl+K Ctrl+T`) and choose a variant

Direct link: [open-vsx.org](https://open-vsx.org/extension/onivoid/oni-dusk-themes)

### From a VSIX (either editor)

1. Download the latest `.vsix` from [GitHub Releases](https://github.com/Onivoid/oni-dusk-themes/releases)
2. Extensions → `⋯` → **Install from VSIX…**
3. Pick the file, then select a theme as above

## Usage

`Cmd+K Cmd+T` (Mac) / `Ctrl+K Ctrl+T` (Windows/Linux) → **Oni Lime**, **Oni Blurple**, **Oni Cyan**, **Oni Magenta**, **Oni Amber**, or **Oni Coral**.

## Develop

```bash
git clone https://github.com/Onivoid/oni-dusk-themes.git
cd oni-dusk-themes
pnpm install
```

Press **F5** (Extension Development Host), or use **Developer: Install Extension from Location…**.

## Release (maintainers)

1. Bump `version` in `package.json` and update `CHANGELOG.md`
2. Commit, tag, and push:

```bash
git tag v0.4.2
git push origin v0.4.2
```

CI (GitHub environment `openvsx`) packages the VSIX, publishes to **Open VSX** (Trusted Publishing) and **VS Marketplace** (if `VSCE_PAT` is set), then creates the GitHub Release.

| Open VSX Trusted Publisher | Value |
|----------------------------|--------|
| Owner | `Onivoid` |
| Repository | `oni-dusk-themes` |
| Workflow | `release.yml` |
| Environment | `openvsx` |

## License

[GPL-3.0](./LICENSE) © Onivoid

This project incorporates work derived from [Bearded Theme](https://github.com/BeardedBear/bearded-theme), © BeardedBear, licensed under the [GNU GPL v3](https://github.com/BeardedBear/bearded-theme/blob/master/LICENSE.txt).
