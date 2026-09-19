# Training – Trainingsplan-App

Eine einzige Datei (`index.html`), läuft als Web-App auf GitHub Pages, ohne Server und ohne Anmeldung.

## Funktionen

- Zwei Splits (Split 1 / Split 2); eine Übung kann an beiden Tagen liegen.
- Pro Übung: Sätze, Ziel-Wiederholungen, aktuelles Gewicht, Steigerungsschritt (kleinste mögliche Erhöhung im Studio).
- Pro Einheit werden die geschafften Wiederholungen je Satz eingetragen.
- **Automatische Progression:** Werden in zwei aufeinanderfolgenden Einheiten einer Übung in jedem Satz die Ziel-Wiederholungen erreicht, steigt das Gewicht um den Steigerungsschritt. Eine verfehlte Einheit setzt den Zähler auf 0.
- Zu jeder Übung eine Illustration mit Start- und Endposition. Neue Übungen bekommen ihr Bild automatisch über den Namen zugeordnet; fehlt ein passendes, wird es im Chat nachgezeichnet und eingespielt.
- Verlauf aller Einheiten, Gewichtsverlauf je Übung, Backup als JSON (Export/Import).

## Daten

Alle Daten liegen im Browser (localStorage) des Geräts, auf dem eingetragen wird. Regelmäßig unter *Übungen → Backup exportieren* sichern.

## Aufs iPhone

Seite in Safari öffnen → Teilen → *Zum Home-Bildschirm*.
