# Risikoanalyse – Woche 3

## Risiko 1: Zu viele Branches führen zu grossem Merge-Aufwand später
Wir haben neben `main` neun weitere Branches. Das ist zu viel und der Merge-Aufwand kann später gross werden.  

- **Eintrittswahrscheinlichkeit**: gross  
- **Gewichtung**: Ein aufwändiger Merge kann das Projekt stark verzögern.  
- **Gegenmassnahme**: Alle Seiten wurden in den `frontend`-Branch gemergt, dieser wird in `develop` integriert, und stabile Releases werden regelmässig nach `main` gemergt.

---
## Risiko 2: Hohe Belastung durch andere Module und Abgaben
Alle haben neben PSE noch andere Module und Abgaben, was unsere verfügbare Zeit für das Projekt einschränkt und den Fortschritt verlangsamen könnte.  
- **Eintrittswahrscheinlichkeit**: gross  
- **Gewichtung**: Zeitmangel kann die Fertigstellung einzelner Komponenten gefährden.  
- **Gegenmassnahme**: Aufgaben werden so verteilt, dass Engpässe durch Abwesenheiten oder Überlastung besser abgefedert werden können.
