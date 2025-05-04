# Risikoanalyse – Woche 9
## Risiko 1: Das Bluetooth-Signal wird vom Sensor nicht erkannt, wenn sich das Gerät nicht in den Bluetooth-Einstellungen befindet.
Die aktuelle Bluetooth-Implementation funktioniert nur, wenn das Gerät sich aktiv in den Bluetooth-Einstellungen befindet. Andernfalls wird das gesendete Signal nicht vom Sensor erkannt. 

- **Eintrittswahrscheinlichkeit**: Gross
- **Gewichtung**: kritisch. Wenn die Sensoren unsere Geräte nicht sehen, können wir vom Broker nicht den Bluetooth-Namen holen.
- **Gegenmassnahme**: Tim untersucht weiterhin mögliche Lösungen mit dem Bluetooth-Adapter. Falls keine praktikable Lösung gefunden wird, wird die Notfalllösung mit der Verwendung der MAC-Adresse implementiert.

## Risiko 2: Ausfall des primären Entwicklungsgeräts (Laptop)
Wenn das primäre Entwicklungsgerät eines Teammitgliedes ausfällt oder kaputt geht, kann es zu Verzögerungen im Arbeitsfluss führen.

- **Eintrittswahrscheinlichkeit**: klein
- **Gewichtung**: mittel. Ein Ausfall könnte zu Verzögerungen führen und das Projekt eventuell gefährden.
- **Gegenmassnahme**: Sicherstellen, dass Projekte und Umgebungen schnell auf Ersatzgeräten eingerichtet werden können. Im Notfall kann man den Computerraum im EXWI benutzen.
