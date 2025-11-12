- Prozessor versucht vorher zu sagen, welche Daten bald gebraucht werden
- Daten werden in den Cache geladen (L1, L2, L3) => schnellerer Zugriff
- Lokalitätsprinzip, Zeitliche und Räumliche Lokalität
- Werte die zuvor gelesen wurden werden werden evtl. wieder gelesen (Stack)
- Werte die in der nähe von anderen sind werden evtl. auch gelesen oder beschrieben
- Gutes Programm wurde unter Beachtung dieser Prinzipien geschrieben
- Teils nur kopieren und in den Cache und löschen für read only
- Oder Write-Thrugh in den Hauptspeicher
- Nur schreiben auf den Cache und später im Hauptspeicher verändern (Write-back)
- Laden von Daten in Blöcken/Zeilen in den Cache und aus dem Cache
- Immer ganze Zeilen (32 bis 128 bit)

![[screenshot 21.png]]

- Direct Mapped: Index beschreibt direkt eine Zeile
- Fully asscoiative: Keine Index-bits 
- N-associative: aufteilung in n sektionen
- Cold miss: Daten waren noch nie im Cache
- Conflict miss: Daten
- Capacity miss: Cache ist voll, hat keinen Platz mehr
- Inklusive Chace Hierachie: Jeder chach hat alle daten von dem davor
- Exklusiver Cache, sind unabhägig von einander

![[screenshot 22.png]]