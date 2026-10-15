# assets/

Drop the showcase images here. The main `README.md` already references these filenames, so once the files exist they render automatically — no edits needed.

| File | What it shows | Notes |
|------|---------------|-------|
| `desk.png` | The full coach's desk scene (the hero shot) | Landscape, ~1600px wide. This is the first impression. |
| `newspaper.png` | The newspaper opened to the standings | The unfold / zoom state, not the folded desk view. |
| `tactic-board.png` | A finished game's tactic board (shot charts + scout) | The signature scene — a visually rich game. |
| `folders.png` | The folders opened to the team index | Shows the "objects are data" idea. |
| `ticket.png` | A single game as a ticket | Fenerbahçe – Partizan. |
| `agenda.png` | The agenda opened to the fixtures | The fixture list as a desk agenda. |
| `demo.gif` *(optional)* | A short recording of the zoom: desk → document → game | Keep it under ~8s and a few MB. Add `![demo](assets/demo.gif)` to the README hero if you include it. |

## Capturing tips

- The 3D scene (react-three-fiber) often comes out blank when captured by automated screenshot tools — take these **manually** from a real browser (macOS: `Cmd+Shift+4`, or a screen recorder → GIF for the demo).
- Prefer a window around 1440–1600px wide so text in the HTML overlay stays crisp.
- PNG for stills; for the GIF, a tool like Gifski or `ffmpeg` gives small, clean output.
