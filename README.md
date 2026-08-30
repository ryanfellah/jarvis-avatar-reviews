# jarvis-avatar-reviews

Exported review media for the Ryan pixel avatar. Published so review files can be
opened from a plain link without signing in.

| File | What it is |
|---|---|
| `latest.png` | Current review — all nine form transitions, ten-form gallery, close-ups, layer views, endpoints |
| `latest.gif` | Current animation — Normal → SSJ1 at 12 fps |
| `index.html` | Self-contained player: transition selector, frame stepping, nine GIFs |
| `manifest.json` | Date, branch, SHAs, frozen-body digest, test results, per-transition lightning |
| `forms/` | Per-sheet PNGs, nine transition GIFs and frame-stepping strips |
| `transformation/` | The body-only cinematic review |
| `before/` | The preserved `bf3eb1e` result |
| `poses/` | The multi-angle pose review |

The four top-level filenames are stable. Each run replaces them in place, so the
links never change. History is kept in this repository's commits.

**Media only.** No source code, credentials, logs, local paths, build files or
private information. Nothing here comes from the application bundle.
