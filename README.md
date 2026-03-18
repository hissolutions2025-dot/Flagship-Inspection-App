# COC Inspection App — Flagship Solar

SANS 10142-1:2024 Electrical Compliance Inspection App for Flagship Solar.

## Features

- **553-point SANS checklist** with pass/fail/N/A and bulk operations
- **Video clips** — record 20-second inspection clips per item (camera + audio)
- **Photo evidence** — inspection and remediation photos with captions
- **Defect tracking** — priority levels, cost estimation, product catalogue
- **Job card** — technician assignment with PIN auth, work notes, 3-state status
- **Estimate builder** — parts, labour, recipes, discount approval, VAT
- **Multi-job management** — create, save, load, delete multiple inspections
- **Reports** — COC status, section progress, technician performance metrics
- **Signatures** — touch/stylus capture for customer and inspector sign-off
- **GPS location** — auto-capture property coordinates
- **Google Drive sync** — backup inspection data to Drive
- **Share/export** — email, native share, download reports
- **Dark mode** — toggle for outdoor visibility
- **Offline PWA** — works without internet, install to home screen
- **SANS clause viewer** — reference SANS 10142-1, 10087-1, 10252-1, 10254

## Files

| File | Purpose |
|------|---------|
| `index.html` | Complete app (single-file HTML/CSS/JS) |
| `sw.js` | Service worker for offline caching |
| `manifest.json` | PWA manifest for home screen install |

## Hosting

This app is hosted via GitHub Pages. All three files must be in the same directory.

The app requires HTTPS for camera, microphone, and service worker features — GitHub Pages provides this automatically.

## Tech Stack

Pure HTML/CSS/JS — no frameworks, no build step, no dependencies. Data stored in browser localStorage.

## Version

v20260309-VID
