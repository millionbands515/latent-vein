# latent-vein

Music visualizer. WebGL2 heightfield raymarcher that listens.

- **Icy** — [Yohei Nishitsuji](https://x.com/YoheiNishitsuji/status/2098403689421570237) `#つぶやきGLSL` marcher (MIT).
- **Latens** — same marcher remixed toward [LATENS](https://x.com/ilumine_ai/status/2098342499865821654) iridescent void-terrain.

Drop a track, pick a file, or use the mic. Bass lifts the ridges, mids warp and shift hue, highs spark flecks, amplitude drives glow and fly speed.

## Run

Open `index.html` in Chrome / Firefox / Safari. No build step.

Mic needs a secure context (`localhost` or https). File drop works from `file://`.

| Input | Action |
| --- | --- |
| Drop / **Load** | Play an audio file |
| **Mic** | Live input |
| `1` / `2` | Icy / Latens |
| Space | Pause the camera (audio keeps driving) |
| Drag | Look |

Not LATENS itself. Visual inspiration only. Yohei's compact source is MIT-licensed as stated on his profile.
