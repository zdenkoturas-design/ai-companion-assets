# AI Companion Assets

Asset repository for the AI companion prototype.

## Structure

```text
assets/
  manifest.json
  MAN/
    MANWORLD.png
    tongnian/MANTN.glb
    chengnian/MANCN.glb
  GIRL/
    GIRLWORLD.png
    tongnian/GIRLTN.glb
    chengnian/GIRLCN.glb
  YAOGUAI/
    YAOGUAIWORLD.png
    tongnian/YAOGUAITN.glb
    chengnian/YAOGUAICN.glb
```

## Rules

- Use Git LFS for model and image assets.
- Keep public runtime URLs in `assets/manifest.json`.
- Keep stage ids stable: `tongnian` for child, `chengnian` for adult.
- Add future stages as new folders, but keep existing paths unchanged.

## Current CDN Source

The app currently reads assets from:

```text
https://iiiiiin.sixeco.com/AIVIDEO
```

When GitHub Pages or another CDN is enabled, update `manifest.json` and the app asset base together.
