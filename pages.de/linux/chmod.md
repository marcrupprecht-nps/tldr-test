# chmod

> Ändern der Zugriffsberechtigungen einer Datei oder eines Verzeichnisses.
> Nachfolgend werden die Befehle beispielhaft am Hinzufügen von Rechten erklärt. Es ist mit einer ähnlichen syntax jedoch auch problemlos möglich Rechte zu entziehen. Hierfür wird das PLUS (+) durch ein MINUS (-) ersetzt.

- Gib dem Besitzer (u=user) einer Datei das Recht diese auszuführen (x=execute):

`chmod u+x pfad/zur/datei`

- Gibt dem Besitzer Leserechte (r=read) und Schreibrechte (w=write) für eine Datei / ein Verzeichnis:

`chmod u+rw pfad/zu/datei_oder_verzeichnis`

- Gib der Besitzer[g]ruppe die Ausführrechte für eine Datei:

`chmod g+x pfad/zur/datei`

- Gib [a]llen Benutzern die Rechte zum Lesen und Ausführen einer Datei:

`chmod a+rx pfad/zur/datei`

Ändere die Schreibrechtefür die Besitzergruppe und andere rekursiv (alle dem aktuellen Verzeichnis untergeordnete Verzeichnisse):

`chmod -R g+w o+w pfad/zum/verzeichnis`

- Gib anderen (o=other) (nicht in der Besitzer[g]ruppe befindliche Benutzer) die gleichen Rechte wie derBesitzergruppe:

`chmod o=g pfad/zur/datei`
