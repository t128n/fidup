- quasi wie [[TCP-IP-Modell#^b4a03f|Routing]], bloß auf [[OSI-Modell|Ebene 2]] bzw. [[TCP-IP-Modell|Netzzugangsschicht]]

## Ablauf
1. eingehendes **Ethernet-Frame** wird **analyisiert**
2. MAC-Adressen und Port Nummern von Sender um Empfänger werden in *MAC-Tabelle* (FDB, Forwarding Database) gespeichert (Einträge werden regelmäßig erneuert da Port-Nummer sich ändern kann)
3. Ethernet-Frame wird an Ziel Port Nummer weitergeleitet

## Quellen

> Switching. (2024, September 17). Retrieved from https://www.elektronik-kompendium.de/sites/net/0907141.htm