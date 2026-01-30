# X-Carve CNC Pre-Flight Checklist

Static checklist and setup guides for X-Carve Pro CNC.

**Live:** [https://zombodotcom.github.io/cncChecklistXcarve/](https://zombodotcom.github.io/cncChecklistXcarve/)

- **Checklist:** [cnc_checklist.html](cnc_checklist.html) (interactive pre-flight checklist)
- **Setup guides:** [ChatGPT-X-Carve Pro 2026 Setup.md](ChatGPT-X-Carve%20Pro%202026%20Setup.md), [Claude-X-Carve Pro setup guide.md](Claude-X-Carve%20Pro%20setup%20guide.md)

## Local development

Run a local server with live reload (edits to `cnc_checklist.html` refresh the browser automatically):

```bash
npm install
npm run dev
```

Opens http://localhost:3000/cnc_checklist.html in your browser. Edit the HTML/CSS and save to see changes.

## GitHub Pages

This repo is published at **https://zombodotcom.github.io/cncChecklistXcarve/**.

To enable or update Pages: **Settings** → **Pages** → **Build and deployment** → **Source:** Deploy from a branch → **Branch:** `main`, folder **/ (root)**. The root URL redirects to the checklist.
