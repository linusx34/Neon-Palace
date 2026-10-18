# Die Website zu GitHub hochladen

Am einfachsten geht das am PC oder Mac im Browser.

1. Lade `Horus-Casino-GitHub.zip` herunter und entpacke die Datei.
2. Öffne https://github.com/new und melde dich an.
3. Trage als Repository-Namen zum Beispiel `horus-casino` ein.
4. Wähle **Private**. Aktiviere **Add a README file**, damit du direkt die Dateiansicht erhältst. Erstelle das Repository mit **Create repository**.
5. Klicke im Repository auf **Add file → Upload files**.
6. Öffne den entpackten Ordner `horus-casino`. Ziehe seinen gesamten Inhalt inklusive der Ordner `assets` und `scripts` in das Upload-Fenster. Lade die entpackten Dateien hoch, nicht die ZIP-Datei und nicht den äußeren Ordner als zusätzliche Ebene. Die mitgelieferte README darf die zuerst angelegte README ersetzen.
7. Trage unten als Beschreibung zum Beispiel `Casino-Website hinzugefügt` ein und bestätige den Upload mit **Commit changes**. Je nach GitHub-Ansicht kann der Abschluss über **Propose changes** und einen anschließenden Pull Request erfolgen.
8. Prüfe die Dateiansicht: `index.html`, `styles.css`, `app.js` und `README.md` müssen direkt auf der obersten Ebene liegen. Unter `assets` muss `vegas-hero.webp` liegen.

GitHub entpackt eine hochgeladene ZIP-Datei nicht automatisch zu einem Projekt.

## Später Änderungen hochladen

Öffne wieder **Add file → Upload files**, lade die geänderten Dateien mit denselben Namen und Pfaden hoch und speichere die Änderung. Für häufigere Änderungen mit mehreren Dateien eignet sich auch GitHub Desktop: https://desktop.github.com/.

## Was passiert mit der bisherigen Website?

Die bisherige Website bleibt unter ihrer vorhandenen Adresse erreichbar:
https://horus-lounge-linus.bubblyhorse4.chatgpt.site

GitHub speichert mit diesem Upload zunächst den Code. Das Repository ist nicht automatisch mit der bisherigen Website verbunden. Für eine Veröffentlichung aus GitHub muss separat ein Hosting eingerichtet oder die Verbindung in einem passenden Entwicklungsworkflow hergestellt werden.

## iPhone oder iPad

In der Dateien-App kannst du die ZIP-Datei durch Antippen entpacken. Für das Hochladen des vollständigen Projekts samt Ordnerstruktur ist ein Computer deutlich bequemer. Wenn du mobil hochlädst, kontrolliere unbedingt, dass der Ordner `assets` mit seiner Bilddatei erhalten bleibt.

Offizielle GitHub-Anleitung:
https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository
