# Lyd Ark Wicca Splash Screen

## Approved visual direction

- Deep midnight-plum / purple night sky.
- One prominent, luminous antique-gold crescent moon.
- One shooting star with a restrained, fading trail.
- The shooting star follows one smooth, open curved sweep above the moon and loops seamlessly.
- The star's path is a motion path only: do not draw it as a visible orbit, ring, loop, or circular outline.
- No stray circle, halo, decorative loop, or line should cross or sit over the moon.
- Keep the crescent clearly visible and unobstructed.
- Calm, graceful motion; avoid flashing, busy particles, or excessive glow.
- Small LYD ARK wordmark beneath the artwork.

## Plasma splash implementation

The first Plasma 6 implementation is in:

`../look-and-feel/org.lydark.wicca.desktop/contents/splash/`

It uses a QML animation and scalable SVG artwork. The package targets Plasma 6.8.3, observed in the Lyd Ark desktop image build logs. Runtime testing is still required on an installed image.

## Boot-stage distinction

KDE's Plasma splash is shown while the logged-in desktop session starts. The earlier pre-login boot screen is handled separately by Plymouth. A matching Plymouth theme will be developed as a separate component so the same moon-and-star identity can appear during system boot.

## Animation states

1. Fade in the night-sky background.
2. Bring up the crescent's warm gold illumination.
3. Animate a single shooting star along the curved path above the moon.
4. Fade the star trail naturally and repeat without a visible jump.
