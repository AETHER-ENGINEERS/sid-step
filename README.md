# SID-STEP

3-voice × 16-step sequencer for Vector / Webxdc. SID constraints, not a reSID port: linear PAL frequency register, one 12 dB lowpass, reSID noise taps (bit 22 XOR bit 17).

Drop `sid-step.xdc` into a Vector chat. `webxdc.js` is injected by the host and is not in the archive.

Open `index.html` in a browser to play. Share stays disabled there. Export wav downloads if `sendToChat` is missing or rejects.

Pack:

```
(cd . && zip -9 -r ../sid-step.xdc index.html manifest.toml icon.png LICENSE)
```

License: AETHER-ENGINEERS Multiversal License. Full text in `LICENSE`. Latest timestamp wins. Canonical: https://github.com/AETHER-ENGINEERS/AETHER-ENGINEERS/blob/main/LICENSE
