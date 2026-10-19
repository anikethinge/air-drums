# 🥁 Air Drums — Play Drums with Your Hands in Real-Time

A responsive, browser-based Air Drum kit powered by your webcam, **MediaPipe Hands** computer vision tracking, and the **Web Audio API**.

Play 8 responsive virtual drum pads in mid-air using hand gestures, or fall back to keyboard / touch controls.

---

## ✨ Features

- **⚡ Real-Time Hand Tracking**: Uses Google's MediaPipe Hands for low-latency fingertip tracking and strike velocity detection.
- **🔊 Realistic Drum Synthesis**: Built entirely on the Web Audio API with zero external audio assets required.
- **🥁 8 Ergonomic Drum Pads**:
  - **Crash Cymbal** (`Q`)
  - **Hi-Hat** (`W`)
  - **Hi-Tom** (`E`)
  - **Mid-Tom** (`R`)
  - **Ride Cymbal** (`T`)
  - **Snare Drum** (`F`)
  - **Floor Tom** (`G`)
  - **Bass / Kick** (`Space`)
- **🎨 Visual Feedback & VFX**: Neon drum ripple effects, mallet tracking, and glowing skeletal overlay.
- **🎛️ Drum Kits**: Switchable kit profiles (Rock Kit, 808 Electronic Kit) with master volume and mute controls.
- **📱 Zero Dependencies / Self-Contained**: Single pure HTML/JS file that works anywhere modern browsers run.

---

## 🚀 How to Run Locally

Because the app uses your webcam (`getUserMedia`), modern browsers require a local HTTP server:

```bash
# Using Python
python3 -m http.server 3000

# Open in your browser:
# http://localhost:3000
```

---

## 🎮 How to Play

1. Allow camera permissions when prompted.
2. Hold your hands up so your fingertips are visible in the camera frame.
3. Strike downwards into any of the 8 drum pads to trigger sounds.
4. Alternatively, use keyboard keys (`Q`, `W`, `E`, `R`, `T`, `F`, `G`, `Space`) or tap directly on the screen.

---

## 📄 License

MIT
