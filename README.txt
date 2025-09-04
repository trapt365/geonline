
# D3 Embed-Ready Package

This folder contains an `index.html` built from your original `competitive_landscape_d3.html` and some light CSS for predictable iframe height. 
Publish it to any static hosting (Vercel/Netlify/GitHub Pages). Then paste the resulting HTTPS URL into Gamma → Insert → Embed webpage.

## Quick Deploy

### Option A: Vercel (no config needed)
1. Create a new project on https://vercel.com (or use Vercel CLI).
2. Drag-and-drop this folder; ensure `index.html` is at the project root.
3. Open the generated HTTPS URL and embed it in Gamma.

### Option B: Netlify Drop
1. Go to https://app.netlify.com/drop
2. Drag-and-drop this folder. Get the HTTPS URL and embed it in Gamma.

### Option C: GitHub Pages
1. Create a repository and upload `index.html` at the root.
2. Enable GitHub Pages (Settings → Pages → Deploy from branch).
3. Use the published HTTPS URL in Gamma.

## Notes
- The page is responsive and sets a minimum height so your viz looks good inside an iframe.
- If your D3 code loads external resources, make sure they are HTTPS and allow embedding (avoid `X-Frame-Options: DENY` and overly strict CSP on your host).
