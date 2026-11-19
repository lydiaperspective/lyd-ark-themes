# Lyd Ark Wicca Plymouth theme

This is the early-boot Plymouth theme for Lyd Ark Linux, separate from the KDE Plasma session splash.

## Design

- Midnight-plum gradient background with the cartoon-inspired golden crescent mark.
- LYD ARK LINUX wordmark.
- Eight antique-gold moon phases with lavender sparkle details.
- Moon phase is selected from Plymouth's reported boot progress; it advances as progress advances and cross-fades gently between phases.
- No rotating spinner, orbit rings, or decorative loops.

## Installation

The desktop image build pins this repository revision, copies this directory to
`/usr/share/plymouth/themes/lyd-ark-wicca`, selects the theme, and regenerates
the initramfs after the final kernel and graphics driver have been installed.

The script also provides password and question prompt callbacks so Plymouth
can continue to display disk-encryption prompts.

## Validation

The theme must be checked in an installed image on Intel and NVIDIA hardware.
Plymouth's progress values depend on the boot path and may not advance uniformly;
the lunar indicator intentionally reflects the progress Plymouth reports rather
than claiming to be a precise task counter.
