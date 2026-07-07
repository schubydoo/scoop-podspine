# scoop-podspine

[Scoop](https://scoop.sh) bucket for [Podspine](https://github.com/schubydoo/podspine) —
a self-hosted server that turns audiobooks into per-chapter podcast feeds.

```powershell
scoop bucket add podspine https://github.com/schubydoo/scoop-podspine
scoop install podspine
```

Podspine needs `ffmpeg`/`ffprobe` on PATH: `scoop install ffmpeg`.

`bucket/podspine.json` is **auto-synced** from the canonical manifest in the main repo
(`schubydoo/podspine`, `packaging/scoop/podspine.json`) by
`.github/workflows/sync-manifest.yml` — don't hand-edit it here.
