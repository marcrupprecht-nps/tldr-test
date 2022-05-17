# ip

> Anzeigen und/oder verändern von IP-Adressen, Routing und Netzwerkgeräten.

- Anzeigen der Netzwerkinterfaces mit detaillierten Informationen (z.B. IP-Adresse v4/v6):

`ip a` oder `ip adress`

- Anzeigen der Netzwerkinterfaces mit weniger Informationen (Name des Interfaces, Status, IP-Adresse):

`ip -brief adress`

- Ein- oder Ausschalten eines bestimmten Netzwerkinterfaces:

`ip link set InterfaceBezeichnung up|down`

- Anzeigen der Routingtabelle

`ip route`

- Hinzufügen oder entfernen einer IP zu einem Netzwerkinterface:

`ip addr add/del IPAdresse/Netzwerkmase dev InterfaceBezeichnung`

- Hinzufügen einer neuen Standardrout zu einem Netzwerkinterface:

`ip route add default via IPAdresse dev InterfaceBezeichnung`


