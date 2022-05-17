# rm

> Löschen von Dateien oder Ordnern.

- Löscht eine Datei im aktuellen Verzeichnis:

`rm Datei1`

- Löscht mehrere Dateien im aktuellen Verzeichnis:

`rm Datei1 Datei2`

- Löscht eine Datei aus einem anderen Verzeichnis als dem aktuellen:

`rm pfad/zur/datei`

- Löscht mehrere Dateien aus einem anderen Verzeichnis als dem aktuellen:

`rm pfad/zur/datei1 pfad/zur/datei2 ...`

- Löscht das angegebene Verzeichnis und dessen  Unterverzeichnisse (inkl. Dateien):

`rm -r pfad/zum/verzeichnis`

- Löscht eine oder mehrere Datei(en). Jeder Löschvorgang muss bestätigt werden:

`rm -i Datei1 (Datei2 ...)`

- Löscht Verzeichnis(se) oder Datei(en) und gibt für jeden Löschvorgang eine detaillierte Information im CLI an:

`rm -v Datei1` oder `rm -r pfad/zum/verzeichnis`
