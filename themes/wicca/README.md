# Lyd Ark Wicca

A cute, polished, Wicca-inspired appearance for KDE Plasma and the early boot experience. The desktop should feel like a premium purple KDE experience first, with a gentle cartoon illustration style and thoughtful Wiccan celestial and nature symbolism.

## Visual identity

- **Style:** rounded cartoon-vector artwork, soft shading, warm highlights, and restrained outlines.
- **Mood:** mystical, peaceful, nature-connected, and charming—not gothic or spooky.
- **Signature motifs:** moon phases and triple-moon imagery, stars, delicate botanical elements, crystals, and occasional subtle pentacle geometry.
- **Artwork balance:** use symbols intentionally. Not every icon needs to be a moon, and the desktop should not be crowded with decorative motifs.

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
- Use antique gold sparingly for selected states, small highlights, and symbolic icon details.
- Keep typography clean and readable.
- Avoid heavy gothic styling, noisy textures, oversized pill controls, and excessive ornament.
- Use botanical and Wiccan-inspired details mainly in branding, wallpapers, splash screens, and selected icons.

## Current cartoon icon family

The SVG assets are original theme artwork and can be used independently in branding, launcher artwork, wallpapers, and future icon-theme work.

| Asset | Motif |
|---|---|
| `icons/lyd-ark-wicca-moon.svg` | Rounded antique-gold crescent with lavender sparkle |
| `icons/triple-moon.svg` | Waxing crescent, full moon, and waning crescent |
| `icons/amethyst-crystal.svg` | Softly faceted amethyst cluster |
| `icons/lavender-sprig.svg` | Lavender flowers and botanical leaves |
| `icons/sage-leaf.svg` | Sage leaves with gentle green shading |
| `icons/pentacle.svg` | Restrained antique-gold pentacle emblem |

These are standalone SVG artwork assets, not yet a complete installable KDE icon theme. A full icon theme needs application and system icon coverage, naming, inheritance, and size variants.

## Boot splash

The early-boot Plymouth theme uses a cartoon-inspired Lyd Ark crescent logo, midnight-plum background, and LYD ARK LINUX wordmark. Eight gold moon phases replace the spinner and advance according to Plymouth's reported boot progress, with a soft cross-fade between phases. The Plymouth theme retains password and question prompts for encrypted installations.

The later KDE Plasma splash remains a separate component and uses the approved golden crescent and shooting-star artwork.

## Component status

- [x] Initial KDE colour scheme (`colors/Lyd Ark Wicca.colors`)
- [x] Plasma 6 startup splash package (QML + SVG artwork; runtime validation pending)
- [x] Plymouth lunar boot theme (progress-linked moon phases; runtime validation pending)
- [ ] Wallpapers with Wiccan celestial and botanical motifs
- [x] Cartoon crescent launcher emblem
- [x] Initial Wicca cartoon SVG icon family
- [ ] Full installable KDE icon theme with application/system icon coverage
- [ ] Optional coordinated cursors
- [ ] Login-screen branding, where supported by the target Plasma version

## System Manager integration

Lyd Ark System Manager should use native KDE/Qt styling and follow the active system palette and Plasma theme. It should not impose a separate Wicca-only layout or spacing system.
