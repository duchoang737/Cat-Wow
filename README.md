# 🐾 Fluffy Cats — Idle Clicker

A cozy idle/clicker game. **Tap the cats** → they get startled, jump, and shed fluff →
**sweep the fur** off the ground to earn coins → buy more cats, upgrade them, unlock the
**skill tree**, and fend off giant **rat bosses**. Dogs and a robot vacuum help you clean up.

**▶ Play:** _(add your link here once deployed — see below)_

## Run locally

It's a single static page — no build step, no server code.

```bash
# just open it:
start index.html          # Windows
# or serve the folder:
python -m http.server 8000    # then open http://localhost:8000
```

## Files

| File | What |
|---|---|
| `index.html` | The whole game — logic, balance, rendering, HUD |
| `cat_assets.js` | All sprites (cats, dogs, rats, fur, vacuum, background) as base64 |
| `CREDITS.md` | Asset sources & licenses |
| `LICENSE` | MIT (code) |

Save data lives in your browser's `localStorage`. Add `?reset` to the URL to wipe progress.

## Deploy (pick one)

- **itch.io** — zip this folder, upload as an HTML5 project, set `index.html` as the main file, tick "This file will be played in the browser." Instant public link.
- **GitHub Pages** — push this folder to a repo, Settings → Pages → deploy from `main` / root. Link is `https://<user>.github.io/<repo>/`.
- **Netlify / Vercel** — drag-drop the folder. Instant link.

## Credits

Cats & dogs by **LuizMelo** (CC0), rats by **Micax** (free). Everything else original.
See [CREDITS.md](CREDITS.md).
