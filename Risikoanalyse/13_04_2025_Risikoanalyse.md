# Risikoanalyse – Woche 6

## Risiko 1: Mindestanforderung bis Ende Semester nicht schaffen
Wir haben fast alle Ziele der Mindestanforderung bereits umgesetzt. 
Das verbleibende Problem betrifft die Bluetooth-Integration. Sollte sich dieses nicht wie geplant lösen lassen, existiert ein funktionierender, aber weniger eleganter Notfallplan.

**Eintrittswahrscheinlichkeit:** gering  
**Gewichtung:** Eine Nichterfüllung der Mindestanforderung hätte Auswirkungen auf die Projektbewertung.  
**Gegenmassnahme:** Umsetzung des funktionierenden Notfallplans, falls das Bluetooth-Problem nicht gelöst werden kann.

## Risiko 2: Kommunikationsprobleme im Team
Bei einem sechsköpfigen Team kann es durch unterschiedliche Zeitpläne, Prioritäten oder Missverständnisse leicht zu Kommunikationslücken kommen, die den Fortschritt verzögern.

**Eintrittswahrscheinlichkeit:** mittel  
**Gewichtung:** Mangelnde Koordination kann zu doppelter Arbeit, Missverständnissen oder vergessenen Aufgaben führen.  
**Gegenmassnahme:** Regelmässige Meetings und transparente Aufgabenverteilung über GitHub Issues.

## Risiko 3: Schwierigkeiten beim Verarbeiten und Visualisieren der Raumdaten
Das Zeichnen des Raumlayouts basiert auf MQTT-Daten, insbesondere den Properties `roomCorners` und `sensors`. Die Struktur dieser Daten ist umfangreich und muss erst analysiert und richtig interpretiert werden.
Da wir gerade erst mit Milestone 2 starten, besteht das Risiko, dass die Komplexität unterschätzt wird oder technische Hürden beim Parsen und Visualisieren auftreten.

**Eintrittswahrscheinlichkeit:** mittel  
**Gewichtung:** Verzögerungen oder Fehlinterpretationen könnten die korrekte Darstellung der Räume beeinträchtigen und den Fortschritt im Milestone 2 verzögern.  
**Gegenmassnahme:** Frühzeitiges Testen der MQTT-Endpunkte mit Tools wie MQTTX oder Postman. Erste einfache Visualisierung rasch umsetzen, um frühzeitig Probleme zu identifizieren.

