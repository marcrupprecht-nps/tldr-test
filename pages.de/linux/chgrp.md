# chgrp

> Ändern des Gruppenbesitzes von Dateien und Verzeichnissen.

- Besitzergruppe einer Datei / eines Verzeichnisses ändern:

`chrgrp GRUPPENNAME pfad/zu/datei-oder-verzeichnis`

- Besitzergruppe eines Verzeichnisses und dessen Inhalt rekursiv ändern:

`chgrp -R GRUPPENNAME pfad/zum/verzeichnis`

- Besitzergruppe eines symbolischen Links ändern:

`chgrp -h GRUPPENNAME pfad/zum/symlink`
