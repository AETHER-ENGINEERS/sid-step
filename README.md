# SID-STEP

Three tracks on one clock: tune, bass, and beat. Pitches are rounded the way the Commodore 64 sound chip did it. The screen is not.

Open [index.html](index.html) in a browser, or drop `sid-step.xdc` into a Vector chat. `webxdc.js` is injected by the messenger and is not packed in the file.

Older builds stay in [archive/](archive/) so each step is still there:

| File | Build |
| --- | --- |
| [archive/sid-step-0.0.1.xdc](archive/sid-step-0.0.1.xdc) | First drop. Clock stuck on the first column. |
| [archive/sid-step-0.0.2.xdc](archive/sid-step-0.0.2.xdc) | Three lanes and note names. Second press of Play scheduled the bar into the future. |
| [archive/sid-step-0.0.3.xdc](archive/sid-step-0.0.3.xdc) | Play survives stop and start. Shared patterns are checked. Hollow-wave cache never hit. |
| [archive/sid-step-0.0.4.xdc](archive/sid-step-0.0.4.xdc) | Saved patterns use the same checks as shared ones. The hollow-wave cache keys on the width. The `webxdc.js` tag was dropped by mistake. |
| [archive/sid-step-0.0.5.xdc](archive/sid-step-0.0.5.xdc) | Script tag restored. Full 24-bit pitch register. `version` is already in the manifest. |
| [archive/sid-step-0.0.6.xdc](archive/sid-step-0.0.6.xdc) | Update listener cannot be torn down by a bad pattern. No master volume control. |
| [archive/sid-step-0.0.7.xdc](archive/sid-step-0.0.7.xdc) | Master volume. One lowpass shared by every track. |
| [archive/sid-step-0.0.8.xdc](archive/sid-step-0.0.8.xdc) | Low, band, and high. Cutoff and resonance were still labeled Tone and Ring. No sample row. |
| [archive/sid-step-0.0.9.xdc](archive/sid-step-0.0.9.xdc) | Cutoff, resonance, and a sample row. The screen stayed black because a pitch label was missing. |
| [archive/sid-step-0.0.10.xdc](archive/sid-step-0.0.10.xdc) | The screen draws. Notes are a short blip. No live keys. |
| [archive/sid-step-0.0.11.xdc](archive/sid-step-0.0.11.xdc) | Envelope, filter wobble, and fine tune. The keys were a second row of note letters, easy to miss. |
| [sid-step.xdc](sid-step.xdc) | 0.0.12. Current. A piano stays pinned to the bottom. White and black keys. |

Press Play. The bright column moves across all three lanes. Pick a note letter, tap a pad to place it, tap it again to clear it.

License: AETHER-ENGINEERS Multiversal License. Full text in `LICENSE`. Latest timestamp wins. Canonical: https://github.com/AETHER-ENGINEERS/AETHER-ENGINEERS/blob/main/LICENSE
