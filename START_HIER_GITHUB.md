# Start hier – vollständige Anwendung auf GitHub Pages veröffentlichen

Diese ZIP enthält die komplette Anwendung einschließlich Quellcode und einem sofort veröffentlichbaren `docs`-Ordner. Die Veröffentlichung kommt ohne versteckten `.github`-Ordner und ohne eigenen GitHub-Actions-Workflow aus.

## Neues Repository

1. Bei GitHub ein neues, leeres Repository anlegen.
2. Die ZIP entpacken.
3. **Den Inhalt des entpackten Hauptordners** in das Repository hochladen – nicht den Hauptordner als zusätzliche Unterebene.
4. Die Änderungen mit **Commit changes** speichern.
5. Unter **Settings → Pages → Build and deployment → Source** den Eintrag **Deploy from a branch** auswählen.
6. Bei **Branch** `main` und daneben den Ordner `/docs` auswählen.
7. Auf **Save** klicken und kurz warten. Die Website-Adresse wird anschließend oben auf derselben Seite angezeigt.
8. Den angezeigten Link zur Website öffnen.

GitHub Pages veröffentlicht den bereits fertigen Ordner `docs`. Auf GitHub muss daher kein `npm install` und kein Build ausgeführt werden.

Die Adresse hat normalerweise dieses Muster:

`https://BENUTZERNAME.github.io/REPOSITORYNAME/`

## Vorhandenes Repository vollständig ersetzen

Den Inhalt dieser Version in das vorhandene Repository hochladen und gleichnamige Dateien ersetzen. Anschließend committen und unter **Settings → Pages** prüfen, dass `main` und `/docs` als Quelle eingestellt sind.

Nach einem Update die Website einmal hart neu laden:

- macOS: `Cmd + Umschalt + R`
- Windows/Linux: `Strg + F5`

## Datenschutz

Keine ausgefüllten Schülerlisten, Projekt-JSON-Dateien, PDF-Listen oder andere personenbezogene Daten in das Repository hochladen. Schülerdaten werden ausschließlich in der veröffentlichten Browseranwendung importiert und lokal verarbeitet.
