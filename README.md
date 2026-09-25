# Nokia Loader — Fling Loader

A playful progress indicator styled like an early-2000s Nokia monochrome LCD. A slingshot bird tries to deliver your message to a mailbox while the send is in progress.

## Live demos

| Version | Link | What it shows |
|---|---|---|
| **Determinate** | https://nokia-loader.vercel.app | Progress is known (0–100%). Dots fill along the rail, and an invisible wall at the current progress stops the bird until the send hits 100%. |
| **Indeterminate** | https://nokia-loader.vercel.app/indeterminate | Progress is unknown. Dots sweep back and forth, a timer counts up, and the mailbox stays closed until the task reports done. |

## How to play

1. Click **SEND** (on screen, or the right / middle key on the phone). The camera leans in.
2. While it loads, drag the bird back and release, or press **LAUNCH**.
3. When the status says **READY!**, launch once more to land the bird in the mailbox.
4. Press **OK** on *MESSAGE SENT* to zoom back out and start over.

## Files

- `index.html` — determinate version
- `indeterminate.html` — indeterminate version
- `vercel.json` — enables clean URLs (`/indeterminate` without `.html`)

Each HTML file is fully self-contained; open it directly in a browser. Timing, status text, colors and launch strength are in the `CONFIG` block at the top of each file's script.
