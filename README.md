# Markup

Browser tool for annotating and measuring field-inspection photos — on-site or off. Phone-first. No backend, no install, nothing uploaded.

**Current version: v1.5.5**

## Features

- **Annotate photos** — freehand draw, text labels, leader notes, polygons, QR stamps, divider cards
- **Measure** — linear length, angle, and area, with manual or camera-calibrated (see below) real-world values
- **Camera calibration** — teach the tool a camera once, then measure real size using distance to the object with no ruler in the shot
- **Defect tagging** — condition-coloured defect chips (CS1–CS4, Unrated) with a reusable material / component / tag / element vocabulary, favourites, recents, and your own added terms
- **Auto-numbering** — incrementing markers with optional letter prefix; each prefix keeps its own count per photo
- **Gestures** — double-tap and hold on tools for quick options: recent values, notes, links and angles; number prefixes; line tips and ends; fill; full-size zoom; export format. Hold (or right-click) an object for colour, size, edit, duplicate, delete
- **Multi-photo sessions** — filmstrip tray, per-photo markup and undo history, photo hotkeys
- **Photo details** — double-tap a thumbnail to set caption and location, reorder or remove the photo, and see the date taken; optional caption and date strip on the photo, in exports and in the report
- **Report (experimental)** — builds a findings schedule from the placed defect chips, editable on screen, printed to PDF via the browser or saved as CSV
  - Setup: rename or hide header fields, columns and sections
  - Editable condition scale (codes, words, which states are used)
  - Presets: Bridge (Austroads/NZTA), Building, or your own; export and import
- **Six languages** — English, Chinese, Spanish, Hindi, Arabic (RTL), Russian
- **Export** — flatten one photo or a whole album at full native resolution, as JPG or PNG

## How it works

- Single self-contained HTML file — vanilla JS, no framework, no CDN, no build step
- Runs entirely in the browser, works offline
- Everything is saved locally on the device and restored on reload — nothing is uploaded

## Usage

1. Open the file in a browser (or use the hosted version)
2. Load photos — drag and drop, paste, pick from device, or capture from camera
3. Pick a tool, mark up the photo
4. Export one photo or the whole album, or print a report

Camera profiles and report presets can be exported and imported as JSON to move them between devices.

## Compatibility

Works in current versions of Chrome, Safari, Firefox, and Edge on phone, tablet, and desktop. iOS uses the native share sheet to save exports to Photos.

## Status

The annotation core, multi-photo session, measurement and multilingual UI are stable. Gestures and the photo details panel are new and not yet tested on real phones. The report is experimental and not yet field-proven — its behaviour may change.

## Privacy

All photos and annotations stay on the device. No account, no upload, no tracking.

## Support

If this tool is useful to you, you can support its development:

- [Ko-fi](https://ko-fi.com/yegorv)
- [Stripe](https://buy.stripe.com/fZu00iemkeuX4wo2GUb7y00)
