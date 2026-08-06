# Amber Glass Phosphor

Amber Glass Phosphor is a dark CRT-inspired theme for Obsidian. It uses embedded WOFF2 fonts, square terminal-style interface elements, restrained scanlines, and a configurable phosphor glow. Everything required by the theme is contained in `theme.css`, so it remains fully usable offline.

## Features

- Amber, green, and white phosphor palettes.
- Embedded offline fonts with no network requests.
- Matching Reading view, Live Preview, interface, and PDF-export styling.
- Optional CRT scanlines and vignette.
- Optional phosphor text glow.
- Square, terminal-inspired controls and panes.
- Style Settings integration.

## Installation

### Manual installation

1. Create a folder named `Amber Glass Phosphor` inside your vault's `.obsidian/themes` directory.
2. Copy `theme.css` and `manifest.json` into that folder.
3. Open **Settings → Appearance → Themes** in Obsidian.
4. Select **Amber Glass Phosphor**.

### Community Themes

Once the theme is accepted into the Obsidian Community directory, it can be installed through **Settings → Appearance → Themes → Manage**.

## Style Settings

The optional [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) community plugin exposes the theme's built-in controls. After enabling the plugin, open **Settings → Style Settings → Amber Glass Phosphor**.

Available controls:

- **Phosphor palette:** Amber, Green, or White.
- **Disable CRT overlay:** Removes scanlines and the edge vignette.
- **Disable text glow:** Removes glow while retaining the selected palette.

Amber remains the default when Style Settings is not installed.

## Fonts

The theme embeds format-converted WOFF2 versions of:

- Share Tech Mono
- 3270 Nerd Font
- Audiowide

The embedded copies use theme-specific internal aliases. Their original copyright notices, project links, and SIL Open Font License information are available in [`licenses/fonts`](licenses/fonts/README.md).

## Publishing checklist

Before submitting the theme to the Obsidian Community directory:

1. Add a 16:9 screenshot; Obsidian recommends 512 × 288 pixels.
2. Commit `README.md`, `LICENSE`, `manifest.json`, `theme.css`, and the `licenses` directory to the repository root.
3. Create a GitHub release tagged `1.0.0`.
4. Attach `manifest.json` and `theme.css` to that release.
5. Submit the repository through [Obsidian Community](https://community.obsidian.md/).

## License

The theme's original CSS and documentation are released under the [MIT License](LICENSE).

The embedded fonts are separately licensed under the SIL Open Font License 1.1. The MIT License does not replace or alter the font licenses.
