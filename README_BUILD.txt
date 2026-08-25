SeaFix Engineering — Android project
App ID: com.seafix.engineering
App name: SeaFix Engineering
Web content: www/index.html
Offline troubleshooting database: 3624 records

Build on a computer:
1) Install Node.js and Android Studio.
2) Open a terminal in this folder.
3) npm install
4) npx cap add android
5) npx cap sync android
6) Open the generated android folder in Android Studio:
   npx cap open android
7) Android Studio -> Build -> Generate App Bundles or APKs -> Generate APKs

For a release intended for Play Store, create a signing key and generate a signed App Bundle (AAB).
Do not delete www/index.html; it contains the offline SeaFix app and database.
