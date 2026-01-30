# X-Carve CNC Pre-Flight Checklist

Static checklist and setup guides for X-Carve Pro CNC.

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

1. Push this repo to GitHub.
2. **Settings** → **Pages** → **Build and deployment**
3. **Source:** Deploy from a branch
4. **Branch:** `main` (or your default branch), folder **/ (root)**
5. Save. The site will be at `https://<username>.github.io/<repo>/` (and `index.html` redirects to the checklist).
