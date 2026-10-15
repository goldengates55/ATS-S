Stockroom: web app (GitHub Pages) and Android APK (GitHub Actions)

WEB APP
Upload all files to the repository root. Pages serves index.html.
When you update: replace index.html and change VERSION in sw.js (e.g. "stockroom-3").

ANDROID APK
Needs: package.json, capacitor.config.json and .github/workflows/build-apk.yml in the repository.
1. Repository > Actions tab > "Build Android APK" > Run workflow.
2. Wait about 5 to 10 minutes. Open the finished run, scroll to Artifacts, download "stockroom-apk" (a zip).
3. Unzip, send app-debug.apk to the phone, tap it and allow installing from this source.
Not included in the app: sync between phones (needs claude.ai).
Licence: put your WhatsApp number in LIC_CONTACT inside index.html (search for it).
