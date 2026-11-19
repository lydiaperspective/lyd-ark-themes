# Lyd Ark Wicca Splash Screen

## Plasma splash

The Plasma 6 session splash is in:

`../look-and-feel/org.lydark.wicca.desktop/contents/splash/`

It uses QML animation and scalable SVG artwork. Runtime validation is still required on an installed image.

## Early boot: Plymouth

The separate early-boot theme is in `../plymouth/`. It replaces the generic Arch branding/spinner with the Lyd Ark Wicca crescent mark and an eight-stage moon-phase indicator. Plymouth's reported boot progress selects the phase; a short cross-fade softens each change.

The theme is packaged into the desktop image's initramfs after the final kernel and graphics driver layers are composed. Password/question callbacks are included so disk-encryption prompts remain usable. The server image remains headless and does not receive the Wicca desktop splash.

Runtime validation is still required on Intel and NVIDIA hardware, including an encrypted installation. The indicator reflects Plymouth's progress estimate, not an exact count of boot tasks.
