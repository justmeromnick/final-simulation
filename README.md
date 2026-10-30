# Circuit Craft — GitHub Pages deployment

Static browser simulation, separated from the original single-file HTML.

## Files
- `index.html` — markup and stylesheet/script references
- `css/style.css` — all 11 original style sections in order
- `js/script-1.js` through `js/script-4.js` — original JavaScript sections, kept separate and in order to preserve their loading and scope behavior

## Deploy
1. Create a GitHub repository (for example, `circuit-craft`).
2. Upload `index.html`, `css/`, and `js/` to the repository root. Keep folders intact.
3. Open **Settings → Pages → Build and deployment**. Set **Source: Deploy from a branch**, select `main` and `/ (root)`, then save.
4. Your site is normally available at `https://YOUR-USERNAME.github.io/circuit-craft/` when GitHub Pages finishes publishing.

## Local test
Open `index.html` in a browser, or use VS Code Live Server. Test each level, the circuit verification, quiz, audio controls, and certificates before public use.

No build step, npm, or Git CLI is required to upload these files through GitHub's website.
