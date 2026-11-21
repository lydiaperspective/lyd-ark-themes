# Lyd Ark Wicca Plymouth theme

This is the early-boot Plymouth theme for Lyd Ark Linux, separate from the KDE Plasma session splash.

## Design

- Midnight-plum gradient background with the cartoon-inspired golden crescent mark.
- LYD ARK LINUX wordmark.
- Eight antique-gold moon phases with lavender sparkle details.
- Moon phases continuously cross-fade in sequence while Plymouth is displaying the splash. The cycle is independent of Plymouth's reported boot progress.
- No rotating spinner, orbit rings, or decorative loops.

## Animation behaviour

The eight phases advance in a repeating cycle and do not claim to represent boot completion. This keeps the animation moving smoothly even when the boot process pauses or Plymouth does not receive useful progress updates.

The animation is implemented through Plymouth's refresh callback, so it does not depend on a separate timer service. Its perceived speed follows the refresh cadence provided by Plymouth.

## Installation

The desktop image build pins this repository revision, copies this directory to /usr/share/plymouth/themes/lyd-ark-wicca, selects the theme, and regenerates the initramfs after the final kernel and graphics driver have been installed.

The script also provides password and question prompt callbacks so Plymouth can continue to display disk-encryption prompts. The animation must never cover or replace those prompts.

## Validation

The theme must be checked in an installed image on Intel and NVIDIA hardware. Verify that the phase sequence continues during slow boot stages and that encrypted installations still accept and display password prompts correctly.
