# Data Submissions

This folder holds contributed session data from Mind Influence Lab users. Every file here is loaded automatically by the [Open Lab](https://wickeddarko.github.io/mind-influence-lab/open-lab/) page and made available for collective analysis.

---

## What goes here

Batch-export CSV files from the Mind Influence Lab app vault (v2.1.0+). These contain only measured and computed numerical data — z-scores, phase analysis, protocol type, environmental readings, coherence scores. No free-text session notes are included in the batch export.

One file per contributor. Name your file something like `username_YYYY-MM.csv` so it's identifiable without being personal.

---

## How to contribute

**Option A — Pull Request (preferred)**

1. Fork this repository
2. Add your exported CSV to this folder (`data/submissions/your_name_date.csv`)
3. Open a pull request with a brief description of how many sessions and which protocols

**Option B — GitHub Issue**

Open an [Issue](https://github.com/WickedDarko/mind-influence-lab/issues/new) with the title `Data Submission`, attach your CSV file, and it will be committed here manually.

---

## Generating your export

In the app:

1. Open the Advanced Vault
2. Tap the download icon in the top-right of the app bar
3. Share the file to yourself (email, Drive, etc.)
4. The file is named `mind_influence_lab_all_*.csv`

That file is what goes here. Individual single-session exports (the detailed stream exports) are not used by the Open Lab page — only the batch summary export.

---

## What the data contains

The batch export has 41 columns including:

| Column | Description |
|--------|-------------|
| `session_id` | Unique session identifier |
| `date`, `time` | Session start |
| `duration_s` | Session length in seconds |
| `rng_protocol` | `live`, `buffered`, or `localEntropy` |
| `qrng_provider` | `outshift` or `anu` |
| `rng_z_score` | Overall session z-score |
| `phase_early_z`, `phase_mid_z`, `phase_late_z` | Per-phase z-scores |
| `dominant_source` | Which RNG source dominated |
| `total_rng_ticks` | Independent measurement events |
| `total_rng_samples` | Binary observations |
| `coherence_score` | Session quality (0–100) |
| `mag_deviation_pct` | Magnetometer deviation from baseline |
| `convergence_events` | Multi-channel anomaly co-occurrences |
| `intention`, `energy`, `stress` | Pre-session self-report |

The batch export does **not** include raw stream data, free-text notes (`pre_note`, `post_note`), or any identifying information beyond what you recorded in the intention field yourself.

---

## Privacy

Nothing in the batch export identifies you. There are no accounts, no device IDs, no IP addresses — the app never had them. The `session_id` is a timestamp-based local identifier with no link to any account. The `intention` field contains whatever you typed before the session — keep that in mind when reviewing your export before submitting.

---

## Terms

By submitting a CSV to this folder you agree that the data may be publicly displayed and analysed on the Open Lab page. You retain ownership of your data and can request removal at any time by opening an Issue.

Submitted data is not modified before being added here — what you submit is what appears. The repository maintainer reserves the right to decline submissions that don't match the expected format or appear to contain fabricated data.
