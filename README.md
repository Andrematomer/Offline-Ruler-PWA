# Offline Ruler PWA

A simple, minimalist, offline-first Progressive Web App (PWA) ruler designed for mobile phone screens in emergency situations. 

Since web browsers cannot natively determine the absolute physical size of a device's screen, this tool allows you to manually calibrate the on-screen scale against a ruler once. The scale calibration persists across sessions.

## Features

- **Offline-First:** Uses a Service Worker to cache all assets. Once loaded on your device, it requires no internet connection to open and function.
- **Persistent Settings:** Calibration settings and unit selections (CM/Inches) are saved directly to `localStorage`.
- **UI Lock:** Configured as a fullscreen PWA to block accidental pinch-to-zoom, swipe-refresh, and rubber-band scrolling during physical measurement.
- **Single-File Core:** Simple file structure utilizing vanilla JS and dynamic SVG generation for clean rendering on high-DPI (Retina) screens.

## Project Structure

```text
├── index.html       # Single-file UI, drawing logic, and layout locking
├── manifest.json    # PWA metadata for installation setup
├── sw.js            # Service Worker for local caching
├── icon.svg         # Clean diagonal ruler vector icon
└── LICENSE          # MIT License