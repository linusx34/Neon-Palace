# Horus Casino

Casino-Arcade mit virtuellem Spielgeld. Vollständiger Export der Website mit acht Spielen, eigenen SVG-Symbolen, Animationen und synthetisiertem Audio.

## Enthalten

- Vier Slots: Temple of Horus, Fruit Society, Midnight Gems und Velvet Sevens
- Roulette, Blackjack, Lucky Dice und Golden Flip
- Guthaben, Favoriten und zuletzt gespielte Spiele im lokalen Browser-Speicher
- Gestaffelt stoppende Walzen, Gewinnlinien, Gewinnanimationen und Sounds
- Leise House-Musik, getrennte Audio-Schalter und Musiklautstärke
- Responsive Oberfläche mit aufklappbaren Regeln und Einstellungen

Temple of Horus ist eine eigene Spielvariante, keine Originalversion von Eye of Horus.

## Dateien

| Datei | Inhalt |
| --- | --- |
| `index.html` | Seite und Oberflächenstruktur |
| `styles.css` | Design, responsive Layouts und Animationen |
| `app.js` | Spiele, Zufallsauswahl, Guthaben, Favoriten und Audio |
| `assets/vegas-hero.webp` | Vegas-Banner |
| `scripts/check.mjs` | Einfacher Syntax- und Dateicheck |
| `GITHUB-ANLEITUNG.md` | Schrittweise Anleitung zum Hochladen |

## Lokal ansehen

`index.html` auf einem Computer im Browser öffnen. Für einen lokalen Webserver im Projektordner ausführen:

```sh
python -m http.server 8000
```

Dann `http://localhost:8000` öffnen. Unter manchen Systemen heißt der Befehl `python3`.

Die Website benötigt keinen Build, keine Installation von npm-Paketen und keinen API-Schlüssel. Für die Google-Schriftarten wird eine Internetverbindung genutzt; bei fehlender Verbindung greifen Ersatzschriftarten.

Audio startet erst nach einer Benutzerinteraktion. Browser-Einstellungen und Lautlosmodus können die Wiedergabe beeinflussen.

## Code prüfen

Mit installiertem Node.js:

```sh
npm run check
```

Der Check prüft JavaScript-Syntax, Einstiegspunkte und notwendige Dateien. Er ersetzt keinen visuellen Browser- oder Hörtest.

## GitHub und Veröffentlichung

Siehe `GITHUB-ANLEITUNG.md`. Die Dateien können direkt im Stammverzeichnis eines GitHub-Repositories liegen. Ein statischer Webhost muss dieses Verzeichnis ausliefern; ein Build-Befehl ist nicht nötig.

Das Hochladen auf GitHub aktualisiert die bestehende Sites-Adresse nicht automatisch. Dieser Export enthält bewusst keine Sites-Projektbindung und keine Zugangsdaten.

## Daten

Es gibt keine Ein- oder Auszahlungen und keinen Server für Nutzerkonten. Browserdaten werden nicht nach GitHub übertragen. Guthaben und Favoriten hängen vom Browser und von der jeweiligen Website-Adresse ab. Bei einer neuen Hosting-Adresse beginnt ein eigener lokaler Spielstand.

## Entwicklungsstand

Der Export übernimmt die aktuelle Implementierung. Spiellogik, UI, Audio und Animationen sind zum Teil über aufeinander aufbauende Funktionen organisiert. Die Trennung in HTML, CSS und JavaScript erleichtert weitere Änderungen; sie ist keine vollständige Überarbeitung der internen Architektur.
