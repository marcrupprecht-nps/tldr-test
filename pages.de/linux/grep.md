# grep

> Hilft dabei Ausdrücke/Wörter/Bezeichnungen in einer Datei oder einem Verzeichnis zu finden.
> Unterstützt die Suche nach Mustern und regülären Ausdrücken.

- Suche nach einem Ausdruck in einer Datei:

`grep SUCHBEGRIFF pfad/zur/datei`

- Suche nach einem EXAKTEN Ausdruck:

`grep -F EXAKTER_SUCHBEGRIFF pfad/zur/datei`

- Suchen nach einem Ausdruck [R]ekursiv im aktuellen Verzeichnis. Zusätzlich werden Zeilen[n]ummern angezeigt und Binärdateien [I]gnoriert:

`grep -RIn SUCHBEGRIFF .`

- Suche nach regulären Ausdrücken, ohne Beachtung von Groß- oder Kleinschreibung (Unterstützung der Sonderzeichen '?', '+', '{}', '()', und '|').

`grep -Ei SUCHBEGRIFF /pfad/zur/datei`

- In[v]ertiere das Ergbnis um bestimmte Asudrücke auszuschließen:

`grep -v BEGRIFF`
