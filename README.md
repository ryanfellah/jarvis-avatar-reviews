# jarvis-avatar-reviews

Exported review media for the Ryan pixel avatar. Published so review files can be
opened from a plain link without signing in.

| File | What it is |
|---|---|
| `latest.png` | Pose review — every base and pose at native size and 8× |
| `latest.gif` | Animation preview — each family in turn |
| `index.html` | Self-contained review player (media embedded, no network calls) |
| `manifest.json` | Date, source branch, source SHA, candidate SHA, test result, PixelLab generation count |

These four filenames are stable. Each run replaces them in place, so the links
never change. History is kept in this repository's commits.

**Media only.** No source code, credentials, logs, local paths, build files or
private information. Nothing here comes from the application bundle.
