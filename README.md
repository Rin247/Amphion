# Amphion — Voice & Instrument Learning App

Amphion is an offline-first Android application designed for vocal training, ear training, and instrument practice. Built with Kotlin, Jetpack Compose, Material 3, and low-latency C++ audio pitch detection, Amphion gives musicians and vocalists real-time visual feedback without subscription paywalls or privacy trade-offs.

---

## 🎵 Key Features & Module Breakdown

### 🎤 Pitch Detection & Vocal Tuner (`pitch`)
- **Current**: Low-latency real-time pitch detection (YIN / McLeod pitch method), cent offset visualizer, musical note display, and vocal range monitor.
- **Planned / Roadmap**: Polyphonic pitch estimation, vibrato rate & depth analyzer, and formant frequency tracker.

### 🎼 Ear Training & Sight-Reading (`exercise`)
- **Current**: Interactive interval identification, chord quality recognition, scale degree training, and sight-singing exercises.
- **Planned / Roadmap**: Adaptive difficulty progression, custom exercise creator, and daily practice streak tracker.

### 🎸 Metronome & Rhythm Trainer (`rhythm`)
- **Current**: Sample-accurate metronome, subdivision patterns, tempo tap, and visual pulse animation.
- **Planned / Roadmap**: Complex polyrhythm generator, accelerating tempo trainer, and song rhythm map creator.

---

## 🏗️ Architecture & Technology Stack

- **Platform**: Android 13+ (minSdk 33, targetSdk 37).
- **UI Shell**: Kotlin, Jetpack Compose, Material 3.
- **Audio Core**: Native C++ Audio Pipeline (`Oboe` / `AAudio` 32-bit float pitch detection).
- **Licensing**: AGPL-3.0.

---

## 🛠️ Building & Running

```bash
./gradlew assembleDebug
./gradlew installDebug
```

---

## 📜 License

Amphion is released under the **GNU Affero General Public License v3.0** (AGPL-3.0). See [`LICENSE`](LICENSE) for details.
