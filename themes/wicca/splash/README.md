# Lyd Ark Wicca Splash Screen

## Plasma splash

The Plasma 6 session splash is in the sibling look-and-feel package at themes/wicca/look-and-feel/org.lydark.wicca.desktop/contents/splash/.

It uses QML animation and scalable SVG artwork. Runtime validation is still required on an installed image.

## Early boot: Plymouth

The separate early-boot theme is in themes/wicca/plymouth/. It replaces the generic Arch branding/spinner with the Lyd Ark Wicca crescent mark and an eight-stage moon-phase indicator. The indicator continuously cycles through the phases and is independent of Plymouth's reported boot progress.

The theme is packaged into the desktop image's initramfs after the final kernel and graphics driver layers are composed. Password/question callbacks are included so disk-encryption prompts remain usable. The server image remains headless and does not receive the Wicca desktop splash.

Runtime validation is still required on Intel and NVIDIA hardware, including an encrypted installation. Confirm that the animation keeps looping through slow boot stages and does not obscure unlock prompts.
