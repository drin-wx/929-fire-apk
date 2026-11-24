# 929 Fire WebView APK

Full-screen Android WebView application para sa `https://929fire.org` na may splash screen at custom app icon.

## Paano Palitan ang Logo (`929.png`)
1. I-rename ang `929.png` mo patungong `logo_929.png` (hindi pinapayagan ng Android resource compiler ang file name na nagsisimula sa numero tulad ng `929.png`).
2. I-overwrite ang file sa `app/src/main/res/drawable/logo_929.png`.

## Paano I-build ang APK sa GitHub Actions
1. I-push ang buong folder sa `main` branch ng GitHub repository mo.
2. Buksan ang **Actions** tab at hintaying matapos ang **Build 929 Fire APK**.
3. I-download ang `929-fire-debug-apk` sa ilalim ng **Artifacts**.
