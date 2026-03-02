# 🧪 Mind Influence Lab

**A consciousness experiment tool for exploring the relationship between focused intention and measurable physical reality.**

[![Android](https://img.shields.io/badge/Android-8.0+-00E5B0?logo=android)](https://github.com/wickeddarko/mind-influence-lab/releases)
[![Version](https://img.shields.io/badge/Version-1.2.0-00E5B0)](https://github.com/wickeddarko/mind-influence-lab/releases)
[![License](https://img.shields.io/badge/License-MIT-00E5B0)](https://github.com/wickeddarko/mind-influence-lab/blob/main/LICENSE)

---

##  About

Mind Influence Lab is a **personal research instrument** designed for individuals interested in exploring consciousness-matter interaction through controlled experiments.

**This is not a game. This is not a meditation app. This is a tool for systematic self-inquiry.**

Inspired by the Princeton Engineering Anomalies Research (PEAR) Lab methodology (1979-2007), this app combines:

-  **System Entropy-Based RNG** — Test for statistical deviations in random bit generation
-  **Magnetometer Sensor** — Monitor environmental magnetic field fluctuations
-  **Accelerometer & Gyroscope** — Track movement and stillness quality
-  **Ambient Noise Measurement** — Log environmental sound levels (dB)
-  **Barometer** — Record atmospheric pressure data
-  **Session Analytics** — Track patterns across multiple sessions

---

##  The Hypothesis

**Can focused intention influence random physical systems?**

This app does **not** claim to answer this question. It provides tools for **you** to collect data and draw **your own** conclusions.



---

##  Reading Room (v1.2 New)

Understand the theoretical foundations before experimenting:

| Module | Content |
| :--- | :--- |
| **PEAR Lab** | Historical context from Princeton's 28-year research program |
| **Heart Coherence & EMF** | Physiological theories linking consciousness to electromagnetic fields |
| **Observer Effect** | Quantum mechanics perspectives on consciousness and measurement |

**All content is presented as hypothesis, not proven fact.** Users are invited to test these theories themselves.

---

##  Experiment Modules

### Module 01 — Lab (~10 min)
Run live sensor sessions with real-time data visualization.

| Sensor | Measurement | Purpose |
| :--- | :--- | :--- |
| RNG | Binary deviation (0/1) | Test for statistical anomalies |
| Magnetometer | μT (microtesla) | Environmental magnetic field |
| Gyroscope | Rotation data | Motion/orientation tracking |
| Accelerometer | Movement quality | Stillness detection |
| Microphone | dB (ambient noise) | Environmental sound level* |
| Barometer | hPa (pressure) | Atmospheric conditions |

*\*Microphone measures amplitude only — NO audio recorded or stored*

### Module 02 — Focus (~5 min)
Breathing exercises and stillness training for pre-session calibration.

- Guided breathing animation
- Stillness quality scoring
- Optional binaural beats (10Hz alpha waves)

### Module 03 — Vault
Complete session history with trend analysis.

- All past sessions with full data
- Coherence score trends over time
- Export data as CSV for external analysis
- Pattern detection across sessions

---

## 🔒 Privacy & Data

| Principle | Implementation |
| :--- | :--- |
| **100% Offline** | No internet connection required |
| **Local Storage Only** | All data stays on your device |
| **No User Accounts** | No login, no email, no tracking |
| **No Cloud Sync** | Data is not transmitted anywhere |
| **No Third-Party SDKs** | No analytics, no ads (v1.2) |
| **User-Controlled Export** | CSV export is manual and optional |

### Sensor Permissions

| Sensor | Permission | Why | Data Stored |
| :--- | :--- | :--- | :--- |
| Magnetometer | None (hardware) | Environmental context | μT values only |
| Accelerometer | None (hardware) | Movement detection | Motion quality score |
| Gyroscope | None (hardware) | Rotation tracking | Rotation data |
| Microphone | `RECORD_AUDIO` | Ambient noise (dB) | **NO audio recorded** — dB values only |
| Barometer | None (hardware) | Atmospheric pressure | hPa values only |

**Microphone Clarification:** The app measures sound amplitude (decibels) only. No audio is recorded, stored, or transmitted. Audio data is processed in real-time and immediately discarded.

---


##  Technical Specifications

| Specification | Value |
| :--- | :--- |
| **Minimum Android** | 8.0 (API 26) |
| **App Size** | ~55 MB |
| **Framework** | Flutter (Dart) |
| **Architecture** | Local-first, offline-capable |
| **Backend** | None (all processing on-device) |
| **Database** | SharedPreferences + Local JSON files |

---

##  Version History

### v1.2.0 (Current) — UI Polish + Reading Room
-  **Reading Room** — 3-tab educational module (PEAR Lab, Heart Coherence, Observer Effect)
-  **Deck Concept UI** — Redesigned home screen with actionable cards
-  **Animations** — Subtle pulsating waves and patterns for "alive" feel
-  **Improved Navigation** — Entire cards are now tappable (no separate buttons)
-  **UX Refinements** — Smoother transitions, cleaner visual hierarchy

### v1.1.0 — Environmental Sensors
-  Microphone (ambient noise measurement)
-  Barometer (atmospheric pressure)
-  Gyroscope (rotation tracking)
-  Sensor toggles (enable/disable per session)
-  Pre-permission disclaimer for microphone

### v1.0.0 — Initial Release
-  RNG system (system entropy-based)
-  Magnetometer monitoring
-  Accelerometer (movement detection)
-  Session data saving + export
-  Profile system (XP, levels, streaks)
-  Focus calibration (binaural beats)

---

## ⚠️ Disclaimers

1. **Research Tool Only** — This app is for educational and exploratory purposes. It is not a medical, diagnostic, or scientific device.

2. **No Proven Claims** — The hypothesis that consciousness can influence random systems is **not established science**. This app provides tools for personal investigation, not validated methods.

3. **Individual Results Vary** — Single sessions are statistically meaningless. Patterns across multiple sessions are required for any meaningful analysis.

4. **Maintain Scientific Skepticism** — Users are encouraged to approach results critically and avoid confirmation bias.

5. **Not Affiliated with PEAR Lab** — This app is inspired by PEAR Lab methodology but is not affiliated with Princeton University or the PEAR research program.

---

##  Support This Research

This app is **free, open, and ad-free** (v1.2). Development is funded by voluntary contributions.

| Method | Link |
| :--- | :--- |
| **Buy Me a Coffee** | [☕ Support Link](https://buymeacoffee.com/kannanlukom) |
| **GitHub Sponsors** | [🐙 Sponsor Page](https://github.com/sponsors/wickeddarko) |

**Your support helps keep this tool free and independent.**

---

##  Contact & Feedback

| Purpose | Method |
| :--- | :--- |
| **Bug Reports** | [GitHub Issues](https://github.com/wickeddarko/mind-influence-lab/issues) |
| **Feature Requests** | [GitHub Discussions](https://github.com/wickeddarko/mind-influence-lab/discussions) |
| **Email** | debunking3am.thoughts@gmail.com |

---

##  License

 See [LICENSE](https://github.com/wickeddarko/mind-influence-lab/blob/main/LICENSE) for details.

---

**Built with Flutter. Free, offline, no tracking.**

*Version 1.2.0 — March 2026*
