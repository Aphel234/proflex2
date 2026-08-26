# Update V9.3 – Vierergruppen für Jugend debattiert

## Ziel

Für einzelne Durchführungen kann jetzt die bestätigte **Variante A** aktiviert werden:

- Jahrgänge **8 und 9 zusammen**: Belegung durch 4 teilbar
- Jahrgang **10 aufwärts zusammen**: Belegung durch 4 teilbar
- beide Wettbewerbsgruppen möglichst ähnlich groß: **weiches Ziel**

Die Teilbarkeit ist hart. Eine Belegung mit beispielsweise 5 Personen in Sek I wird nicht als gültiges Ergebnis ausgegeben. `0`, `4`, `8`, `12` usw. sind zulässig.

## Bedienung

1. Unter **Workshops** bei der gewünschten Durchführung auf **„Jahrgänge & Debatte …“** klicken.
2. **„Vierergruppen verbindlich aktivieren“** einschalten.
3. Den weichen Gruppenausgleich nach Wunsch aktiviert lassen oder ausschalten.
4. Vorgaben übernehmen und die Zuteilung neu berechnen.

Im Kursdetail zeigt die Anwendung anschließend die Zahlen für Sek I und Sek II sowie die Differenz des weichen Ausgleichs an.

## Verhalten bei Konflikten

Der Optimierer versucht zulässige Einzelverschiebungen und Tausche. Dabei bleiben Mindest-/Maximalbelegung, Jahrgangsgrenzen, Sperrungen, feste Setzungen und andere harte Regeln erhalten. Ist keine gültige Lösung möglich, erscheint eine konkrete Fehlermeldung statt einer stillen Regelverletzung.

Manuelle Verschiebungen und Tausche werden ebenfalls gegen die Vierergruppenregel geprüft.

## Excel und Kompatibilität

Das Blatt **`Workshops`** enthält zwei zusätzliche Spalten:

`Vierergruppen 8/9 + 10+ | Gruppenausgleich`

Zulässige Werte sind `Ja` und `Nein`. Alte JSON-Projekte und Excel-Dateien bleiben kompatibel; ohne neue Angabe ist die Vierergruppenregel ausgeschaltet.

## Tests

Die Tests decken zusätzlich ab:

- automatische Reparatur auf gültige Viererzahlen
- konkrete Fehlermeldung bei einer durch feste Setzungen unmöglichen Verteilung
- deaktivierte Standardregel für ältere Projekte
