# Brainstorm

Brainstorm is a message-mapping tool. Write the message you plan to send, then branch out the replies you expect. Every message is written by you, and no reply is treated as more likely than another.

- Double-click a bubble to edit it.
- Select a bubble and start typing to reply, or hover over one for a moment and type to branch from it.
- Drag empty space to pan, or scroll. Pinch on a trackpad or touchscreen, or Ctrl/Cmd + scroll, to zoom at that spot.
- Click a message to select it, then drag it to move it; its replies come along.
- Ctrl + click empty space (or Cmd + click on a Mac) to start a new flowchart. The picker opens as you press: slide to Received (gray) or Sent (blue) and let go, or let go first and click one. R and S choose too, and Esc closes it.
- Play a path walks the flowchart you have selected (or any one of them, each with the same chance), picking one reply at random at every branch. Each reply at a branch has the same chance, and the path is lit only while it plays.
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

## Selecting and moving

Click a message to select it. It rises onto a pane of glass, and its actions appear above it as chips that show their keys: Reply (Tab), Edit (Enter), Fold and Unfold (← and →), and Delete (Delete or Backspace). Letters are left alone, because typing any letter starts a reply.

Press a selected message and drag it to move it. It lifts while you drag, and its replies come along. Dragging a flowchart's first message moves the whole flowchart. Where you put things is saved with the map.

## Toolbar and zoom

The buttons sit in glass groups: Play a path on its own, Fit with Center selected, Expand all with Collapse all, and Reset map. Settings is the gear at the right, next to the zoom: minus, the current percentage, and plus. Click the percentage to go back to 100%.

Two-finger zoom works on the canvas everywhere: a trackpad pinch (which Chrome, Edge and Firefox send as Ctrl + scroll), two fingers on a touchscreen, and Safari's own pinch gesture. The zoom follows your fingers, so the spot between them stays put.

## Pointer and flowcharts

Over empty canvas the pointer is an arrow with a small move badge, so dragging pans; while you pan, the badge looks pressed. Hold Ctrl (Cmd on a Mac) and the badge becomes a gray and blue bubble with a plus, meaning a press there starts a new message. These are native cursor images, drawn at 1x and 2x, so they never lag behind the mouse.

A map can hold several flowcharts. A new one starts where you pressed, and its first message is ready to type into. A flowchart's first message can be deleted, taking its flowchart with it, as long as another flowchart is left. Maps saved before flowcharts open exactly where they were.

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
