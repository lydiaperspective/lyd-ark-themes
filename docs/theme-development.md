# Theme development

## Compatibility first

Target the KDE Plasma version used by the current Lyd Ark images. Confirm the installed Plasma version before choosing package metadata or QML APIs. Avoid assuming that a Look-and-Feel or splash package written for one Plasma major version will work unchanged on another.

## Component order

1. Validate the Wicca colour scheme in Plasma.
2. Build the Look-and-Feel package around supported KDE metadata and components.
3. Implement the boot splash as a KDE Splash Screen package.
4. Add wallpapers and launcher artwork.
5. Add optional icon, cursor, and login-screen integration.
6. Package, install, test, and document upgrade/removal.

## Layout preservation

Breeze is the reference for geometry. Theme work must not alter widget spacing, margins, padding, control sizes, or navigation layout unless a separate accessibility issue requires it.

## Application integration

Lyd Ark System Manager should use Qt/KDE palette and style integration so it follows the active system theme. Avoid hard-coded Wicca colours in application widgets.

## Splash animation requirements

The Wicca splash concept uses a golden crescent moon against a deep purple night sky, with one shooting star following a smooth curved path. The path must not become a visible orbit or ring around the moon. No stray circle, halo, or line should cross the moon. The animation should loop smoothly and remain visually calm.
