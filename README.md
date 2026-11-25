# VOIDHOST – öffentliche Design-Demo

Diese Version ist eine **statische Website-Demo** für GitHub Pages.

## Enthalten
- Startseite im dunklen VOIDHOST-Design
- Demo-Anmeldung und Registrierung im Browser
- Übersicht / Meine Server / Monitoring
- Server-Konfigurationen mit 10 Spieler-Slots, 5 GB RAM und 1000 % CPU-Wunschlimit

## Wichtige Grenzen
- Die Demo verwendet nur Browser-Speicher (localStorage). Konten und Server-Konfigurationen funktionieren ausschließlich in dem Browser und auf dem Gerät, auf dem sie angelegt wurden. Sie werden nicht auf einem Server gespeichert oder zwischen Geräten synchronisiert.
- Das ist **keine echte sichere Online-Authentifizierung**. Bitte verwende kein Passwort, das du anderswo nutzt, und gib keine persönlichen Daten ein.
- Server-Erstellen speichert nur eine Demo-Konfiguration. Es wird kein Minecraft-Prozess gestartet.
- Monitoring zeigt keine erfundenen Live-Messwerte; dafür wird später ein lokaler PC-Agent benötigt.
- Die Seite benötigt keinen kostenpflichtigen Hosting-Tarif. GitHub Pages ist bei öffentlichen Repositories mit GitHub Free verfügbar. Siehe die GitHub-Dokumentation: https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages

## GitHub Pages einschalten
1. Öffne das Repository `brunokunze13-maker/bob`.
2. Öffne **Settings → Pages**.
3. Bei **Build and deployment** wähle **Deploy from a branch**.
4. Wähle Branch `main` und Ordner `/(root)`, dann **Save**.
5. GitHub veröffentlicht die Seite unter `https://brunokunze13-maker.github.io/bob/`. Der erste Build kann ein paar Minuten dauern.

GitHub Pages hostet hier nur die statische Demo. Es hostet keinen Minecraft-Server und ist nicht als Backend für ein SaaS mit echten Benutzerkonten gedacht.
