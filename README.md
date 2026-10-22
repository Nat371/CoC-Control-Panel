# CoC Control Panel Android — Prototype 1.1.0

Independent native Android Kotlin project based on the ZIP supplied in chat.

## Included
- Dark dashboard UI.
- Locally saved controls and target settings.
- Local demo license key `COCCP-DEMO-2026` (7-day local demo) and one-time 24-hour local trial.
- GitHub Actions build workflow for a debug APK.

## Limitations
- Local demo license is only for testing; it is not a secure commercial licensing backend.
- Feature switches save configuration only. This build does not connect to or automate Clash of Clans.
- OCR, live screen matching, overlay, and automated gameplay engine are not implemented.

## Build
Open Actions > Build Android APK > Run workflow. Download artifact `CoC-Control-Panel-APK` after a successful run.
