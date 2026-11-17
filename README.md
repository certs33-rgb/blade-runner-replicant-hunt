# BLADE RUNNER // REPLICANT HUNT

A neon cyberpunk action shooter built by Shadow as a browser-based HTML5 canvas game.

## Play locally

Serve this directory with a static web server, for example:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000 in a modern browser. See `README.txt` for controls.

## Hosting

This is a static site: no dependency installation, build command, backend, or API keys are required. The publish directory is the repository root (`.`), and the entry point is `index.html`.

A GitHub-connected static hosting provider can deploy the `main` branch and automatically redeploy on subsequent pushes. Hosting is not configured by this initial upload. A private repository requires granting the chosen hosting provider access; a deployed website can still be public even when the source repository is private.

## Updating

This repository initially contains a clean snapshot of `~/Documents/Shadow_Output/blade-zelda/`. Shadow's original working directory is unchanged and is not automatically synchronized with this repository. To publish a later version, copy the reviewed updated game and required assets into this checkout, then commit and push to `main`.

## Included files

- `index.html`: game code
- `art-title.webp`, `art-win.webp`: artwork used by the game
- `icon.png`: browser icon
- `README.txt`: original run instructions and controls

Historical alternate builds, backup files, archives, and unused artwork are intentionally excluded. No license or rights to third-party names or artwork are granted by this upload.
