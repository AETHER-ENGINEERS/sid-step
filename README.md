# SID-STEP

Three tracks on one clock: tune, bass, and beat. Pitches are rounded the way the Commodore 64 sound chip did it. The screen is not.

Open [index.html](index.html) in a browser, or drop `sid-step.xdc` into a Vector chat. `webxdc.js` is injected by the messenger and is not packed in the file.

Older builds stay in [archive/](archive/) so each step is still there:

| File | Build |
| --- | --- |
| [archive/sid-step-0.0.1.xdc](archive/sid-step-0.0.1.xdc) | First drop. Clock stuck on the first column. |
| [archive/sid-step-0.0.2.xdc](archive/sid-step-0.0.2.xdc) | Three lanes and note names. Second press of Play scheduled the bar into the future. |
| [sid-step.xdc](sid-step.xdc) | 0.0.3. Play survives stop and start. Shared patterns are checked before they touch the engine. |

Press Play. The bright column moves across all three lanes. Pick a note letter, tap a pad to place it, tap it again to clear it.

License: AETHER-ENGINEERS Multiversal License. Full text in `LICENSE`. Latest timestamp wins. Canonical: https://github.com/AETHER-ENGINEERS/AETHER-ENGINEERS/blob/main/LICENSE
