# mv

> Dateien oder Verzeichnisse verschieben und/oder umbenennen.
> Alle Flags können sowohl beim verschieben und/oder umbenennen von Dateien als auch Verzeichnissen genutzt werden.


- Datei umbennen:

`mv pfad/zur/datei pfad/zur/zieldatei`

- Verschieben mehrerer Dateien in ein neues Verzeichnis (Namen der Dateien werden beibeihalten):

`mv datei1 datei2 datei3 pfad/zum/neuen/verzeichnis`

- Überschreiben einer Datei inkl. Bestätigungsaufforderung

`mv -i pfad/zur/datei pfad/zur/zieldatei`

- Verschieben einer Datei mit Angaben zur durchgeführten Aktion und dem neuen Dateinamen:

`mv -v pfad/zur/datei pfad/zur/zieldatei`

- Verschieben eines Verzeichnisses:

`mv tolles/verzeichnis1 tolles/verzeichnis2`
