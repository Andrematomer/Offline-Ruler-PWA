# Offline Ruler PWA

**Live Link:** [click here](https://andrematomer.github.io/Offline-Ruler-PWA/)

A simple, offline-first Progressive Web App (PWA) ruler for mobile screens, featuring manual calibration and draggable guidelines.

## Quick Start

### 1. Calibrate the Screen
1. Open settings (Gear icon) and tap **Unlock**.
2. Align a physical ruler with your screen.
3. Adjust the slider (or `+`/`-`) until the tick marks match exactly.
4. Tap **Lock** to save and protect your calibration.

### 2. Use Guidelines
- **Create:** Long-press on the left or bottom ruler margins.
- **Move:** Drag the guide handles along the margins.
- **Delete:** Drag any handle off the edge of the screen.
- **Distance:** Badges automatically display the distance between adjacent guides.

## Features

- **Offline Support:** Service worker enables full functionality without cell service.
- **Persistent Scale:** Saves your CM/Inch scale settings directly to `localStorage`.
- **Absolute Coordinate Scaling:** Guides stay aligned when switching units (e.g. 2.0 cm stays fixed at 0.79 inches).
- **PWA Optimized:** stand-alone full-screen setup with disabled pinch-to-zoom to prevent accidental screen changes.

## License
MIT License.