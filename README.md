# Orbital Decay — voice-over audio

Voice-over files for the *Orbital Decay* point-and-click demo, served to the game through the jsDelivr CDN.

- `vo/<id>.mp3` — one file per spoken line (mono, 24 kHz, 48 kbps)
- `vo.json` — maps `"<speaker>|<line text>"` to a file id

Generated with [Kokoro TTS](https://huggingface.co/hexgrad/Kokoro-82M) by the game's `build-vo.mjs` script.
The game loads a pinned tag (e.g. `@v1`), so publish changes as a new tag.
