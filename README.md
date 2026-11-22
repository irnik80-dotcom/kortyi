# Kortyi 💧

Gamifikált vízivó app (HTML/JS + Capacitor, Android APK).

- Web verzió: https://irnik80-dotcom.github.io/kortyi/
- Az app forrása: `docs/index.html` (egyetlen fájl)
- Automatikus frissítés: a telepített app induláskor a `docs/version.json` alapján letölti az újabb verziót.
  Új kiadáshoz: növeld a `var V=` számot az `index.html`-ben és a `docs/version.json`-ben is.

## APK építése
```bash
npm install
npx cap sync android
cd android && ./gradlew assembleDebug
```
