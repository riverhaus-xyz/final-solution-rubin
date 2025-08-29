# Zoomed Particle Animation

A standalone HTML animation inspired by https://www.thewayofcode.com/#56.

## Features
- Pure HTML/JS (no React, no build step)
- Controls for width, height, and background color
- Ready for GitHub Pages hosting
- Easily embeddable in Cargo.site via iframe

## How to Use
1. **Preview Locally:**
   - Open `index.html` in your browser.
   - Or run a local server:
     ```sh
     cd zoomed-particle-animation
     python3 -m http.server
     # Then open http://localhost:8000 in your browser
     ```
2. **Host on GitHub Pages:**
   - Push this folder to a new GitHub repository.
   - Enable GitHub Pages in repo settings (set source to `main` branch, `/root`).
   - Your animation will be live at `https://<your-username>.github.io/<repo-name>/`.

3. **Embed in Cargo.site:**
   - Use this iframe code:
     ```html
     <iframe src="https://<your-username>.github.io/<repo-name>/index.html" width="550" height="550" style="border:none; background:#F0EEE6;"></iframe>
     ```
   - Change `width`, `height`, and `background` as needed.

## Customization
- Use the controls at the top of the animation to change size and background color.
- You can further edit `index.html` for more advanced style changes.

---
**Credit:** Animation logic adapted from The Way of Code, #56.
