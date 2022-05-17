# tl;dr für NETWAYS Professional Services

Das **NPS-tldr Projekt** ist eine Sammlung verschiedener, häufig verwendeter, CLI Befehle. Während die bekannten Manpages eine ausführliche Beschreibung des Befehls und dessen Flags bringen, kann das besonders im Arbeitsalltag oder für CLI-Einsteiger unnötig umfangreich sein. Denn in den meisten Fällen werden keine ausführlichen Erörterungen benötigt, sondern lediglich eine kurze, alltagsnahe Erklärung was die Ausführung von Command + Flag bewirkt.

Hier soll das **NPS-tldr Projekt** Abhilfe schaffen. Es soll zukünftig als aktiv genutztes Nachschlagewerk dienen, dass von allen NPS-Mitarbeitenden erweitert und gepflegt wird.

## tldr-Client
Um NETWAYS tldr im eigenen Terminal zu nutzen ist ein entsprechender Client nötig, der die Möglichkeit mitbringt eigene Repositorys einzubinden. Die Funktion des Einbindens verschiedener Repos ist jedoch nicht bei jedem Client gegeben. In diesem Abschnitt wird für jedes Betriebssystem ein entsprechender Client vorgestellt, der diese funktion besitzt und daher zur aktiven Nutzung von **tldr** geeignet ist.

### Debian / Ubuntu
Der standardmäßige **tldr-Client** von Debian / Ubuntu, der mit dem Befehl `apt install tldr` installiert wird, besitzt standardmäßig nicht die Möglichkeit eigene Quellen hinzuzufügen. Ein Client der diese Option besitzt und der deshalb genutzt werden sollte ist der *Python tldr-Client*.
Installationsanleitung:

- `apt install python3-pip`
- `pip3 install tldr`

Hier kann nun mit `tldr -s HIER_MUSS_DIE_URL_STEHEN` das NETWAS tldr-Repo hinzugefügt werden

### Fedora / RedHat

### Windows

### MacOS
