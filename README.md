# Zara for Android - AI agent with full phone control (v2)

## Build (GitHub, no PC tools needed)
1. Create a private repo, upload the CONTENTS of this folder (include the .github folder).
2. Open the Actions tab. When the run is green, download "zara-debug-apk" from Artifacts.
3. If the run is red, open the run page and read the "Build errors" box at the top of the Summary.

## Build (Android Studio)
File > Open > this folder, wait for sync, press Run with your phone plugged in.

## First-time setup on the phone
1. Install the APK. Open Zara > "Enable accessibility" > Zara > ON.
   If the toggle is greyed out: Settings > Apps > Zara > (3 dots) > Allow restricted settings.
2. Paste your Anthropic API key > Save.
3. Speak or type, e.g. "Open YouTube and search lo-fi music".

## Safety
- Floating panel shows what Zara is doing. Stop cancels instantly.
- Yes/No prompt before payments, deleting, finance apps and non-dictated messages.
- Never types passwords/OTPs. Banking apps that block accessibility will look blank.
- API key stays in app-private storage and is excluded from backups.
