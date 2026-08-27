# Patch V9.5.0 installieren

Dieser Patch ist für die vollständige Version V9.4.0 vorgesehen. Er enthält nur neue beziehungsweise geänderte Dateien.

## GitHub-Upload

1. Diese ZIP entpacken.
2. Den **Inhalt** des entpackten Patch-Ordners in das Stammverzeichnis des vorhandenen GitHub-Repositorys hochladen.
3. Bei allen Rückfragen **gleichnamige Dateien ersetzen**.
4. Die Änderungen mit `Commit changes` speichern.
5. Wenn GitHub Pages aus `main /docs` veröffentlicht, muss keine weitere Einstellung geändert werden.
6. Nach der Veröffentlichung die Anwendung einmal hart neu laden:
   - macOS: `Cmd + Umschalt + R`
   - Windows/Linux: `Strg + F5`

Wichtig: Nicht den Patch-Ordner selbst als zusätzliche Unterebene hochladen. Im Repository müssen beispielsweise direkt `docs`, `public`, `src` und `package.json` sichtbar sein.

## Sofort wirksam auf GitHub Pages

Für die veröffentlichte Website sind insbesondere diese Dateien entscheidend:

- `docs/index.html`
- `docs/assets/app.js`
- `docs/sw.js`

Die übrigen Dateien halten Quellcode, Tests, Build-Ausgabe und Dokumentation auf demselben Versionsstand.

## Inhaltliche Änderungen

- Vollständige Zuteilung steht vor der Einhaltung von Zusammensetzungsregeln.
- Eine Jahrgangsregel darf die Zahl unzugeteilter Schüler nicht erhöhen.
- Nicht exakt erfüllbare Regeln erzeugen eine Bestmöglich-Zuteilung mit konkreten Hinweisen.
- Hinweise erscheinen beim Kurs und bei den zugeteilten Schülern.
- „Debattierregel“ heißt jetzt „Jahrgangsgruppen-Regel“.
- Alte JSON-Projekte und alte Excel-Spalten bleiben importierbar.

Die technische Beschreibung steht in `UPDATE_V9_5_0_BESTMOEGLICHE_ZUTEILUNG.md`.

