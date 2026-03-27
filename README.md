# VoiceCounter

A sleek, mobile-optimized Progressive Web App (PWA) designed for guided mobility workouts and interval training. It features a customizable, precise Text-To-Speech (TTS) countdown engine that dynamically adapts to your pacing and exercise rhythms.

## Features

- **Smart Interval Engine:** Highly precise counting powered by dynamic Speech Synthesis API event listener callbacks to eliminate drifting out of sync.
- **Advanced Rhythm Profiles:** Supports default numeric counting (`1`, `2`, `3`), half-beat "And" intervals (`1`, `and`, `2`, `and`), and fast quarter-beat 4-count tempos.
- **Directional Audio Profiles:** Group repetitions into intelligent sets like `Left & Right` or `Forward & Backward`—the voice will dynamically guide you through sides without manual tweaking.
- **Glassmorphic UI:** Modern, distraction-free interface configured natively for mobile device viewports with robust offline-ready characteristics and `Wake-Lock` functionality to prevent the screen from dimming.
- **Easy Import/Export:** Entire workout sequences are seamlessly stored locally in your browser, and can be exported cleanly to JSON for sharing or cross-device backups.

## Live Demo

Accessible anywhere with zero installation directly through GitHub Pages:
👉 [Play VoiceCounter Live](https://banister4728.github.io/voice-counter/)

## Local Development

If you want to run it locally or tweak the code:
1. Clone the repository.
2. Spin up a local server in the directory (e.g. `python3 -m http.server`).
3. You must serve it over `HTTPS` or `localhost` to allow the Web Speech API and Wake-Lock APIs to function securely.
