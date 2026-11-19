# Lyd Ark Wicca

A modern, elegant, mystical appearance for KDE Plasma. The desktop should feel like a premium purple KDE experience first, with subtle celestial character second.

## Palette

| Role | Name | Hex |
|---|---|---|
| Main background | Midnight Plum | `#21152E` |
| Raised surfaces | Deep Royal Plum | `#30203F` |
| Primary accent | Royal Purple | `#583477` |
| Highlight | Amethyst | `#9874C4` |
| Restrained accent | Antique Gold | `#B69A55` |
| Soft text | Soft Lavender | `#D7C8E8` |
| Warm light text | Warm Ivory | `#E9E1D5` |

## Appearance rules

- Breeze is the layout and spacing reference. Do not independently change margins, padding, widget dimensions, or control spacing.
- Use consistent, modest corner rounding compatible with Breeze.
- Use antique gold sparingly for selected states, small highlights, and occasional icon details.
- Keep typography clean and readable.
- Avoid heavy gothic styling, noisy textures, oversized pill controls, and excessive ornament.
- Use subtle celestial or botanical details mainly in wallpapers and branding.

## Boot splash concept

A luminous golden crescent moon in a deep purple night sky. A single shooting star travels along a graceful curved arc near the moon and loops seamlessly. There must be **no orbital rings, no decorative loops around the moon, and no stray circle or halo crossing over the moon**. Keep the crescent clearly visible and the animation calm.

The splash should use the night-sky artwork as its visual foundation. Animation and final packaging will be implemented after the static composition is approved.

## Planned components

- [x] Initial KDE colour scheme (`colors/Lyd Ark Wicca.colors`)
- Plasma Look-and-Feel package
- [x] Plasma 6 startup splash package (QML + SVG artwork; runtime validation pending)
- [ ] Plymouth pre-login boot splash (separate component)
- Wallpapers
- [x] Initial scalable crescent launcher emblem (`icons/lyd-ark-wicca-moon.svg`)
- Optional coordinated icons and cursors
- Login-screen branding, where supported by the target Plasma version

## System Manager integration

Lyd Ark System Manager should use native KDE/Qt styling and follow the active system palette and Plasma theme. It should not impose a separate Wicca-only layout or spacing system.
