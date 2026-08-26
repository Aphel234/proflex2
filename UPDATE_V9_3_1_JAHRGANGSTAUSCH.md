# Update V9.3.1 – Tauschsuche für harte Jahrgangsgrenzen

Die Reparatur harter Jahrgangs-Minima und -Maxima prüft jetzt zusätzlich atomare Tauschaktionen zwischen zwei Kursen.

Das ist insbesondere erforderlich, wenn:

- ein Kurs bereits seine Mindestbelegung erreicht hat,
- ein anderer Kurs vollständig belegt ist und
- die Jahrgangsgrenze nur durch den Tausch zweier Schüler eingehalten werden kann.

Beispiel: Social Media enthält 11 Schüler aus Jahrgang 8, erlaubt sind höchstens 8. Statt die Berechnung abzubrechen, kann das Programm nun Achtklässler gegen zulässige Schüler anderer Jahrgänge aus bereits vollen Kursen tauschen.

Eine Person bleibt erst dann unzugeteilt, wenn weder eine zulässige Verschiebung noch ein zulässiger Tausch gefunden wurde.
