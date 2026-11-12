# Pino-Coach (MVP)

Kommunikations-Coach für Hundehalter: Die App hört während einer Session auf den Namen des Hundes,
analysiert Kommandos (Wiederholungen, uneinheitliche Wörter, Name ohne Folge, Lob/Tadel) und gibt
Verbesserungsvorschläge.

- Web-Oberfläche: `www/index.html`
- Android-Hülle: Capacitor 7 (`android/`), native Spracherkennung über `@capacitor-community/speech-recognition`
- Build: GitHub Actions (`.github/workflows/android.yml`) baut bei jedem Push eine Debug-APK und hängt sie an ein Release.

Lokal: `npm ci && npx cap sync android`, dann `android/` in Android Studio öffnen.
