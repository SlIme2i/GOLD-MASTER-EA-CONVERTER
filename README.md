# GOLD MASTER EA CONVERTER V1 PRO

Android starter project for a local MT4-to-MT5 source conversion assistant.

## V1 limits
- Accepts pasted MT4 source and applies a small set of text-level mappings.
- Output is an uncompiled MQL5 draft, not a guaranteed conversion.
- No broker connection, no order execution, and no EA runtime.
- Live trading is not implemented.
- Validate/compile in MetaEditor and test with MT5 Strategy Tester on a desktop MT5 installation. MT5 Android does not run EAs.

## Build APK using GitHub Actions
1. Create a GitHub repository and upload the contents of this project.
2. Open Actions and run **Build Android APK** (or push to main).
3. Open the successful workflow run and download the artifact named `GOLD-MASTER-EA-CONVERTER-debug-apk`.
4. Extract the ZIP and install `app-debug.apk` on your Android device, allowing installation from that source if Android asks.

Use only source code you own or are authorized to modify. Never use an unreviewed generated EA with a live account.
