# Brainstorm

Brainstorm is a message-mapping tool. Write the message you plan to send, then branch out the replies you expect. Every message is written by you.

- Double-click a bubble to edit it.
- Select a bubble and start typing to reply, or hover over one for a moment and type to branch from it.
- Drag empty space to pan. Ctrl/Cmd + scroll to zoom.
- Your map is saved in your browser.

## Bubbles

The bubbles are measured from iPhone screenshots of iMessage: the same corner radius, tail, colors, text size and line spacing. Blue bubbles shade from lighter at the top of the map to deeper at the bottom, the way Messages does. On Apple devices the text uses SF Pro; elsewhere it uses the free Inter font, adjusted on load to match SF Pro's size, spacing and position.

## Run locally

Open `index.html` in any modern browser. No install or server is needed.

## Publish on GitHub Pages

1. Create a new repository on GitHub named `brainstorm` (public, no README).
2. In this folder, run:
   ```
   git remote add origin https://github.com/YOUR-USERNAME/brainstorm.git
   git push -u origin main
   ```
3. On GitHub, open Settings, then Pages. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, then save.
4. After a minute, the site is live at `https://YOUR-USERNAME.github.io/brainstorm/`.

Because the page is a single HTML file, it works on GitHub Pages without any build step.
