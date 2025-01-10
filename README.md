# flyer-tracker
**Wann wurde wo von wem zuletzt geflyert?**

Link zur Webseite: https://gruenlink.de/zuy3byw7wg

## Neue Einträge hinzufügen
Alle Einträge sind in der Datei `log.geojson` gespeichert. Diese Datei kann online mit GeoJSON.io bearbeitet werden:

https://geojson.io/#id=github:t-karcher/flyer-tracker/blob/main/log.geojson&map=13.5/48.113/11.535

Zu jeder dort eingezeichneten Linie müssen 3 Parameter ergänzt werden: 
* `who`: Wer hat geflyert?
* `when`: Wann wurde geflyert?
* `text`: Kurze Beschreibung des Gebiets (Straße, Hausnummern, ...)

Am Ende der Bearbeitung kann das Ergebnis als GeoJSON-Datei gespeichert und `log.geojson` damit überschrieben werden. (Entweder per Merge-Request direkt in Github, oder per Mail oder Signal-Nachricht an mich)
