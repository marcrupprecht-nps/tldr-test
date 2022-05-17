# cat

> Der Befehl umfasst zwei Funktionen.
> 1. Verketten (zusammenfügen) mehrerer Dateien in einer neuen Datei.
> 2. Ausgabe des Inhalts einer oder mehrerer Dateien im Terminal.

- Gib den Inhalt einer Datei im Terminal aus:

`cat pfad/zur/datei`

- Verkette die Inhalte mehrerer Dateien und speichere das Ergebnis in einer neuen Datei:

`cat pfad/zu/datei1 pfad/zu/datei2 > pfad/zur/neuen_datei`

- Verkette die Inhalte mehrerer Dateien und hänge das Ergebnis an eine bestehende Datei an:

`cat pfad/zu/datei1 pfad/zu/datei2 >> pfad/zur/zieldatei`

- Nummerieren der im Terminal ausgegebenen Zeilen:

`cat -n pfad/zur/datei`

- Ausgabe des Inhalts einer Datei inkl. aller unsichtbaren Leerzeichen (werden mit $ angezeigt):

`cat -v -t -e pfad/zur/datei`
das Ergebnis an eine bestehende Datei an:

`cat pfad/zu/datei1 pfad/zu/datei2 >> pfad/zur/zieldatei`

- Nummerieren der im Terminal ausgegebenen Zeilen:

`cat -n pfad/zur/datei`

- Ausgabe des Inhalts einer Datei inkl. aller unsichtbaren Leerzeichen (werden mit $ angezeigt):

`cat -v -t -e pfad/zur/datei`

