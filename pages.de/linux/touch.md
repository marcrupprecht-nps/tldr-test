# touch

> Dieser Befehl bietet zwei Funktionen.
> 1. Erstellen einer neuen Datei.
> 2. Anpassen der Zugriffs- und Änderungszeiten einer Datei.

- Erstellen einer neuen, leeren Datei oder ändern der Änderungszeit auf die aktuelle Uhrzeit:

`touch pfad/zur/datei(.txt, .md, ...)`

- Erstellen oder Zeitanpassung mehrerer Dateien:

`touch pfad/zur/datei{1,2,3}(.txt, .md, ...)` ODER `touch datei1(.dateiendung) datei2.(dateiendung)`

- Uhrzeit einer Datei auf ein bestimmtes Datum und eine bestimmte Uhrzeit stellen:

`touch YYYYMMDDHHMM.SS pfad/zur/datei`

- Uhrzeit einer Datei eine Stunde zurückstellen:

`touch -d "-1 hour" pfad/zur/datei`

- Übertrage die Uhrzeit einer Datei auf eine andere:

`touch -r pfad/zur/datei1 pfad/zur/datei2`
