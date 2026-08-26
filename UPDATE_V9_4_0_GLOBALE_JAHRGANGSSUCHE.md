# Update V9.4.0 – Globale Jahrgangssuche

Die Jahrgangsregeln werden nicht mehr ausschließlich durch lokale Einzelverschiebungen und direkte Zweiertausche repariert.

## Neue Suchreihenfolge

1. Schnelle lokale Verschiebungen und Tauschaktionen.
2. Globale Neuberechnung mit Min-/Max-Schranken für alle Kurse und Jahrgänge gleichzeitig.
3. Dabei können auch Verschiebungsketten über drei oder mehr Kurse gefunden werden.
4. Nur wenn keine exakte Lösung existiert, wird automatisch die Verteilung mit der kleinsten Jahrgangsabweichung berechnet.

Im Bestmöglich-Fall wird die Berechnung nicht mehr mit einer roten Fehlermeldung abgebrochen. Das Ergebnis erscheint mit einem gelben Hinweis, der Kurs, Jahrgang, Ist-Wert und Zielgrenze nennt. Alle übrigen Kapazitäten, Sperrungen, festen Setzungen und harten Regeln bleiben verbindlich.

Die Wunschqualität wird weiterhin optimiert. Bei einer unvermeidbaren Abweichung hat jedoch zunächst die kleinstmögliche Abweichung von den Jahrgangszielen Vorrang.
