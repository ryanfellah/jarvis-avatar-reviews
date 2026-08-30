# jarvis-avatar-reviews

Exported review media for the Ryan pixel avatar. Published so review files can be
opened from a plain link without signing in.

| File | What it is |
|---|---|
| `latest.png` | Current review — 25-frame transformation contact sheet, native/8×, endpoints, logo strip, crop overlay |
| `latest.gif` | Current animation — the 25-frame transformation at 12 fps |
| `index.html` | Self-contained frame-stepping player (media embedded, no network calls) |
| `manifest.json` | Date, source branch, source SHA, candidate SHA, test results, PixelLab generation count |
| `before/` | The preserved `bf3eb1e` result, kept as the BEFORE comparison |
| `transformation/` | Per-check sheets and the BEFORE/AFTER side-by-side GIF |
| `poses/` | The previous multi-angle pose review, preserved |

The four top-level filenames are stable. Each run replaces them in place, so the
links never change. History is kept in this repository's commits.

**Media only.** No source code, credentials, logs, local paths, build files or
private information. Nothing here comes from the application bundle.
