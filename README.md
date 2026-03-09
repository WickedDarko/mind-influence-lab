# Mind Influence Lab

**A personal consciousness research instrument for Android.**

Explore the relationship between focused intention and measurable physical reality — using genuine quantum random numbers, multi-sensor environmental recording, and longitudinal statistical analysis. Inspired by the methodology of the Princeton Engineering Anomalies Research (PEAR) Lab (1979–2007).

> *visit: https://wickeddarko.github.io/mind-influence-lab/*

---

## What it does

The Advanced Lab runs structured four-phase sessions that record six independent physical channels simultaneously:

| Channel | Source | What is measured |
|---|---|---|
| **Quantum RNG** | Cisco Outshift QRNG API (vacuum fluctuations) | Z-score deviation from theoretical 50/50 baseline |
| **Magnetometer** | On-device hardware | Ambient magnetic field (μT), baseline-referenced |
| **Ambient sound** | Microphone (dB only — no audio recorded) | Environmental acoustic level |
| **Barometer** | On-device hardware | Atmospheric pressure (hPa) |
| **WiFi RSSI** | Connected network | Signal strength deviation across session |
| **Bluetooth** | Nearby devices | RSSI variance — RF environment shifts |

Sessions produce a z-score, phase analysis (early / mid / late intention periods computed independently), a spatial heatmap showing multi-channel convergence events, and a coherence score reflecting session data quality. All results are stored locally. The vault tracks longitudinal patterns across your full session history.

---

## The experimental design

The hypothesis follows the logic established by PEAR: if mind-matter interaction produces any effect on random physical systems, the most statistically detectable signature would appear in a system governed by pure chance. Any systematic deviation from the expected distribution stands out against the noise floor in a way that no deterministic system allows.

**Three RNG protocols test different questions:**

- **Live Quantum** — Numbers generated tick-by-tick during your session. Tests real-time mind-matter interaction.
- **Buffered Quantum** — A batch fetched at session start, consumed during your intention phase. If deviations appear here, real-time causation is ruled out — the only accounts are retrocausal, which is what PEAR's retrocognitive trials documented.
- **Local Entropy** — Device cryptographic RNG seeded from hardware entropy. Useful as a corroborating layer; not independent of the device's physical environment and therefore not the primary experimental channel.

Multi-channel convergence — when quantum RNG and an independent physical sensor deviate in the same five-second window — is the strongest result pattern, as it reduces the range of mundane explanations.

---

## Getting started

### Requirements

- Android 8.0 (API 26) or higher
- ~55 MB storage
- Internet connection for quantum RNG (falls back to local entropy gracefully)

### Install

Download the latest APK from [Releases](https://github.com/wickeddarko/mind-influence-lab/releases) and enable **Install unknown apps** for your browser or file manager in Android settings.



---

## Privacy

- **No accounts, no login, no tracking**
- **No analytics or crash reporting SDKs**
- **No audio captured** — microphone permission reads dB amplitude only; no audio is stored or transmitted
- **One external connection** — Cisco Outshift QRNG API for random number generation only
- All session data stays on-device

See [Privacy Policy](https://wickeddarko.github.io/mind-influence-lab/privacy-policy.html).

---

## Reading Room

The app includes nine in-depth articles covering the scientific and philosophical context:

1. **The Princeton RNG Experiments** — PEAR methodology, findings, and the retrocognitive trials
2. **The Observer Effect** — The measurement problem and consciousness in quantum mechanics
3. **Heart Fields & Coherence** — HeartMath research and bioelectromagnetics
4. **Quantum Interpretations** — Copenhagen, Many Worlds, Transactional, and retrocausality
5. **The RNG Hypothesis** — The three protocols and what each experimental question implies
6. **The Science of Consciousness** — Hard problem, IIT, Orch-OR, Global Workspace Theory
7. **Reading Your Results** — Z-scores, phase analysis, coherence, and multi-channel convergence explained
8. **Running a Good Session** — Protocol, environment, intention framing, and control sessions
9. **The Value of Null Results** — File drawer problem, Bayesian reasoning, and epistemic discipline



---

## Support

Free and ad-free. If you find it useful:

[☕ Buy Me a Coffee](https://buymeacoffee.com/kannanlukom) · [🐙 GitHub Sponsors](https://github.com/sponsors/wickeddarko)

---

## Disclaimer

This app is for educational and exploratory purposes only. It is not a medical, diagnostic, or scientific device. The hypothesis that consciousness can influence random physical systems is not established science. Single sessions are statistically inconclusive — patterns across many sessions are required for any meaningful analysis. Not affiliated with Princeton University or the PEAR research program.

---

## License

See [LICENSE](LICENCE.txt) for details.

---

*Built with Flutter · Free · Offline-first · No tracking · v2.0.0*


