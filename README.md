# Bewerberdaten in JSON standardisieren
## Erste Idee für ein Datenformat für Bewerbungen

Die Datei *data.json* enthält die Bewerberdaten, die aus einem noch zu erstellenden Formular-Input generiert wird. 
Das simple Frontend *index.html* gibtg die Bewerberdaten in Tiles wieder. 

Zum Start dieser kleinen Anwendung empfiehlt sich folgende Vorgehensweise:

1. Klone das GitHub Respo `<https://github.com/CarstenHennig/ApplicantsJSONData>`
2. Öffne den Folder z.B. in VS Code
3. Klicke in VS Code auf "Go Live" (Footer)

### Hintergrund der Idee
Zur Standadisierung werden im Bewerberformular sog. Muss- und Kann-Felder definiert.
Zudem werden Upload-Inputs für Bewerberfoto, CV, Arbeitszeugnisse (mehrere), Anschreiben, sonstige Dateien (z.B. Zertifikate) freigeschaltet. ==Speicherung dieser Uploads ist zu klären==

### Weitere Inmprovements
Im Benchmark zu zeitgemäßen Bewerbertools wie z.B. von *Personio* sind folgende Funktionen erwägenswert:
- Bewerben mit Profilen von LinkedIn, Xing und anderen Business Networks
- Login-Bereich zum Status-Abruf der aktuellen Bewerbungen ==Sehr komplex in der Eigenentwicklung==
