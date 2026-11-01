# Econo High CRI Backlight

A minimal, offline-capable, portrait PWA for the iPad Pro / iPhone.

- **Illumination:** top 80% of screen.
- **Controls:** bottom 20%, black background.
- **Modes:** White, Red, Green, Blue, Cyan, Yellow, Magenta.
- **Colour:** CSS `color(display-p3 ...)` primaries (with sRGB fallback).
- **Operation:** no menus, no scrolling or zooming. Selected mode is remembered.

## iPad / iPhone installation

In **Safari**, open [the Pages app](https://mejtoogood.github.io/econo-high-cri-backlight/), then **Share → Add to Home Screen**. Open it from its Home Screen icon for standalone presentation without Safari's address bar and toolbars. The PWA requests portrait orientation, but iOS ultimately controls orientation locking and system overlays.

For stable colour and output, turn off **True Tone**, **Night Shift** and automatic brightness, and set hardware brightness manually. A web app cannot directly set the display's hardware brightness or change its OLED emission wavelengths. **Display P3 gamut does not imply high CRI.**
