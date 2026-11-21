# Lyd Ark Themes

Official visual themes and desktop branding for Lyd Ark.

## Themes

- **Mystical** — a cute, polished lunar KDE Plasma theme built around midnight plum, royal purple, amethyst, antique gold, moon symbolism, crystals, and botanical artwork.
- **Lyd Ark Cute** — a clean, cheerful pastel theme with pink as its primary colour and lavender as a secondary accent. (Planned)

## Design principles

- Preserve KDE Breeze's default layout, spacing, sizing, and interaction patterns.
- Change appearance, not application geometry.
- Keep Lyd Ark applications native to the active KDE Plasma theme.
- Prefer KDE-native theme formats and settings over application-specific styling.
- Use a shared, polished cartoon-vector illustration language while giving each theme its own motifs and palette.
- Keep artwork and decorative details primarily in wallpapers, splash screens, icons, and branding assets.
- Provide readable contrast and clear focus, hover, selected, and disabled states.

## Repository layout

```text
themes/
  mystical/
    colors/
    look-and-feel/
    splash/
    wallpapers/
    icons/
    cursors/
    README.md
  cute/
    README.md
docs/
  cartoon-artwork-guide.md
  theme-development.md
```

## Status

Mystical is packaged as a Plasma Look-and-Feel theme named **Mystical**, so it is listed in System Settings → Appearance → Global Theme. Its defaults apply the Mystical colour scheme and Plasma splash. The separate Plymouth boot theme loops through eight moon phases. A starter set of original cartoon SVG artwork is included. Runtime validation and broader KDE component integration remain in progress. The Cute theme is planned.
