# Privacy Policy — Mind Influence Lab

**Last Updated:** March 2, 2026
**Version:** 1.2.0

---

##  Overview

Mind Influence Lab is a **research tool**. This privacy policy explains what data is collected, how it is used, and your rights as a user.

**Summary:** This app collects **no personal data**, stores **everything locally**, and transmits **nothing to external servers** 
---

##  Data Collection

###  What We Collect

| Data Type | Purpose | Storage Location |
| :--- | :--- | :--- |
| **Session Data** | Experiment results (RNG deviation, sensor readings) | Local device storage |
| **Profile Data** | XP, levels, streaks, achievement progress | Local SharedPreferences |
| **Environmental Data** | Noise levels, magnetic field, pressure, gyroscope | Local device storage |
| **App Usage** | Session timestamps, duration, feature usage | Local device storage |

###  What We Do NOT Collect

| Data Type | Status |
| :--- | :--- |
| **Personal Identifiers** | ❌ Not collected (no name, email, phone) |
| **Location Data** | ❌ Not collected (no GPS, no network location) |
| **Contact Information** | ❌ Not collected (no contacts, no call logs) |
| **Browsing History** | ❌ Not collected |
| **Device Identifiers** | ❌ Not collected (no IMEI, no advertising ID) |
| **Audio Recordings** | ❌ Not recorded (microphone measures dB only) |
| **Cloud Data** | ❌ Not transmitted (100% offline in Basic Mode) |

---

##  Sensor Permissions

###  Microphone (Optional)

| Aspect | Details |
| :--- | :--- |
| **Permission** | `RECORD_AUDIO` |
| **Purpose** | Measure ambient noise levels (decibels) for environmental context |
| **What Is Stored** | dB values only (numeric amplitude) |
| **What Is NOT Stored** | No audio recordings, no speech, no sound content |
| **Processing** | Real-time amplitude calculation, audio data immediately discarded |
| **Optional** | Yes — can be disabled in settings, app functions fully without it |

### Storage Permissions

| Aspect | Details |
| :--- | :--- |
| **Permission** | `READ_EXTERNAL_STORAGE`, `WRITE_EXTERNAL_STORAGE` |
| **Purpose** | Save session data and export/import CSV files |
| **What Is Accessed** | App-specific folder only (`/Android/data/com.example.mind_control_test/`) |
| **What Is NOT Accessed** | User's personal files, photos, music, other app data |
| **Optional** | No — required for core functionality (data export) |



### Other Sensors (No Permissions Required)

| Sensor | Purpose | Data Stored |
| :--- | :--- | :--- |
| **Magnetometer** | Environmental magnetic field | μT values |
| **Accelerometer** | Movement detection | Motion quality score |
| **Gyroscope** | Rotation tracking | Rotation data |
| **Barometer** | Atmospheric pressure | hPa values |

---

##  Data Storage

| Aspect | Details |
| :--- | :--- |
| **Storage Location** | Android internal storage (`/Android/data/com.example.mind_control_test/`) |
| **Encryption** | Android sandbox protection (app-specific storage) |
| **Backup** | User-controlled (manual CSV export) |
| **Deletion** | Automatic when app is uninstalled |
| **Access** | App only (no other apps can access) |


---

##  User Rights

| Right | How to Exercise |
| :--- | :--- |
| **Access Your Data** | Open Vault screen → View all sessions |
| **Export Your Data** | Vault → Export → CSV file |
| **Delete Your Data** | Uninstall app (all data deleted automatically) |
| **Disable Sensors** | Settings → Toggle individual sensors off |
| **Switch to Basic Mode** | Settings → Select Basic Mode (no location permission needed) |
| **No Account Required** | No login means no account deletion needed |

---

##  Children's Privacy

| Policy | Details |
| :--- | :--- |
| **Age Restriction** | 13+ recommended (research tool, not designed for children) |
| **Parental Consent** | Not required (no personal data collected) |
| **COPPA Compliance** | Not applicable (no personal data collected) |

---

##  Changes to This Policy

| Aspect | Details |
| :--- | :--- |
| **Notification** | Updated policy will be shown in app on next launch |
| **Effective Date** | Changes apply immediately upon app update |
| **Archive** | Previous versions available on GitHub repository |

---

##  Contact Information

| Purpose | Details |
| :--- | :--- |
| **Developer** | Wicked Darko (Individual Developer) |
| **Email** | debunking3am.thoughts@gmail.com |
| **GitHub** | https://github.com/wickeddarko/mind-influence-lab |
| **Response Time** | Within 7 business days |

---

**By using Mind Influence Lab, you acknowledge that you have read and understood this privacy policy.**

*Version 1.2.0 — March 2, 2026*
