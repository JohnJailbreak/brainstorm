# Brainstorm

Brainstorm is a message-mapping tool. Write the message you plan to send, then branch out the replies you expect. Every message is written by you, and no reply is treated as more likely than another.

- Double-click a bubble to edit it.
- Select a bubble and start typing to reply, or hover over one for a moment and type to branch from it.
- Drag empty space to pan. Ctrl/Cmd + scroll to zoom.
- Play a path walks the map from your first message, picking one reply at random at every branch. Each reply at a branch has the same chance, and the path is lit only while it plays.
- Your map is saved in your browser.

## Reply lines

Each reply is joined to the message above it by a line. By default (Intelligence), a new line draws in with a glow in Siri's colors and rings the reply as it lands. Open **Settings** to pick another style; your choice is saved in this browser.

A line animates only when it appears or while Play a path walks it. Lines already on the map stay put when you edit, and a reply you are typing into is never hidden by an entrance. Every line looks the same at rest. If your system is set to reduce motion, lines appear without animation.

| Style | What it does |
| --- | --- |
| Thread | A hairline that turns into each reply on a rounded corner, like inline replies in Messages. |
| Freeform | A soft curve with a small arrowhead, like Freeform. Hover a line to see its handles. |
| Reply count | Hairlines, plus a glass capsule that counts the replies where a message branches. Click it to fold them. |
| Liquid Glass | A glass stem that pools where it meets each bubble and catches the light from your pointer. |
| Pencil | Each line is written in like a pen stroke. |
| Typing | Typing dots appear where a reply is about to show, then grow into the bubble. |
| Droplet | Each reply buds off the message above it and pinches free, leaving a fine strand. |
| Magic Move | A copy of the message lifts off and turns into the reply on its way down. |
| Spring | Replies drop in on a spring. Swipe across a line to pluck it. |
| Focus | During Play a path, the message being played stays sharp and the rest soften. |
| Route | During Play a path, a Maps location puck drives along the lines being played. |
| Activity | Every line sits on a track that fills while Play a path walks it, then empties. |
| Intelligence (default) | Light in Siri's colors runs down each new line and rings the reply. |
| Siri wave | Soft waves along every line that swell when a reply arrives. |
| Invisible Ink | Sparkles drift down every line; new replies arrive covered in ink. |

## Bubbles

The bubbles are measured from iPhone screenshots of iMessage: the same corner radius, tail, colors, text size and line spacing. Blue bubbles shade from lighter at the top of the map to deeper at the bottom, the way Messages does. On Apple devices the text uses SF Pro; elsewhere it uses the free Inter font, adjusted on load to match SF Pro's size, spacing and position. A row of the map grows to fit its tallest message, so long messages keep the same room for their reply lines.

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
