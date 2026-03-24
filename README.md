Panacea Sound (zzfxm Edition)
Panacea Sound is a standalone, procedural music engine and synthesizer toy. It is a specialized port of the JACTunes/JACTUBE engine, powered by the ZzFXM (ZzFX Music) framework. This version is completely self-contained with no external dependencies, utilizing the Web Audio API to generate infinite, high-fidelity chiptune, lofi, and ambient compositions directly in the browser. There also exists a webaudio version with a similar featureset.

Live Demo Here - https://jerseysignalproject.github.io/panaceazz/

🚀 Features
Procedural Composition: Generates unique tracks on the fly using mathematical scales and rhythm templates.

ZzFXM Core: Leverages the tiny but powerful ZzFX/ZzFXM audio tiny-engine for synthesis.

Extended Playback: Default track length is optimized for ~3 minutes of continuous play, with a configurable "SEQ LEN" slider for even longer durations.

Live Editor: Real-time control over BPM, Sustain, Swing, Oscillator types (Sine, Square, Sawtooth, Triangle), and per-track FX (Reverb, Echo, Pan).

Rhythm Grid: Manually toggle steps for Lead, Bass, and Percussion patterns.

WAV Export: High-quality offline rendering to export your procedural creations as .wav files.

Batch Export: One-click export for the entire generated library.

🛠 Tech Stack
Audio Engine: ZzFX & ZzFXM (MIT License)

Environment: Pure HTML5 / JavaScript (ES6+)

Audio API: Web Audio API (OfflineAudioContext for rendering)

📦 Installation & Usage
Download the panacea.html file.

Open it in any modern web browser (Chrome, Firefox, Edge, Safari).

Click "REGENERATE" to create a new batch of 50 procedural tracks.

Use the Editor panel to tweak the synthesizers and effects in real-time.

🎹 Customization
You can modify the core generation logic within the JT object:

Scales: Add new musical modes to the scales object.

Progressions: Define new chord movement patterns in progressions.

Default Length: To change the default duration, look for the targetSec variable in the genLibrary function (currently set to 180 seconds).

📄 License
This project is open-source and builds upon the ZzFX and ZzFXM engines created by Frank Force and Keith Clark.

Created as a standalone evolution of the JACTunes synthesizer toy.
