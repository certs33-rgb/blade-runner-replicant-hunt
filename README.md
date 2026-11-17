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

Play online: https://certs33-rgb.github.io/blade-runner-replicant-hunt/

GitHub Pages publishes the repository root from `main`. Push updated `index.html` and its required assets to `main`; GitHub will rebuild and publish the game at the same URL. Friends can also launch it from Dixon's Projects: https://dixon-projects.workspace-619203.chatgpt.site/

## Updating

This repository initially contains a clean snapshot of `~/Documents/Shadow_Output/blade-zelda/`. Shadow's original working directory is unchanged and is not automatically synchronized with this repository. To publish a later version, copy the reviewed updated game and required assets into this checkout, then commit and push to `main`.

## Included files

- `index.html`: game code
- `art-title.webp`, `art-win.webp`: artwork used by the game
- `icon.png`: browser icon
- `README.txt`: original run instructions and controls

Historical alternate builds, backup files, archives, and unused artwork are intentionally excluded. No license or rights to third-party names or artwork are granted by this upload.
