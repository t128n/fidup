- Strategie zur **Beseitigung und Vermeidung von Redundanz** in relationalen Datenbanken 

> *"Normalisierung bezeichnet man **die Überführung** einer Datenbanktabelle in eine **Normalform höheren Grades**. Die Überführung in eine Normalform **geringeren** Grades wird **Denormalisierung** genannt."*
> - https://www.ionos.de/digitalguide/hosting/hosting-technik/normalisierung-von-datenbanken/anomali

## Normalformen

1. **1. Normalform (1NF)**, alle Daten liegen *atomar* vor, Tabellenspalten beinhalten *gleichartige Werte*
2. **2. Normalform (2NF)**, jedes *Nichtschlüsselattribut* muss vom *Primärschlüssel voll funktional abhängig* sein
3. **3. Normalform (3NF)**,  *kein Nichtschlüsselattribut* darf von einem *Schlüsselkandidaten transitiv* abhängig sein

## Vorteile
- **weniger Redundanz**
- **Verhinderung** von **Anomalien**
- **spezialisiertere Abfragen** möglich
## Nachteile
- Integration von **Fremdschlüsseln**
- viele **Joins erforderlich**
- bei größeren Datensätzen mit vielen Abhängigkeiten, **viele Tabellen**

## Beispiel
- Ausgangslage
![\1](attachments/\1)
- **1NF**, *mehrwertige Daten* aufspalten, Spalten auf *Gleichartigkeit* prüfen
![\1](attachments/\1)
![\1](attachments/\1)
- **2NF**, Spalten die nicht *voll funktional abhängig* sind, werden ausgelagert (`Anz.` ist nur von `P.-Nr.` abhängig aber nicht `R.-Nr.`, daher wird `P.-Nr.` und abhängige Spalten ausgelagert.)
![\1](attachments/\1)
![\1](attachments/\1)
- **3NF**, Spalten die von einem *Nichtschlüsselattribut abhängig* sind, werden ausgelagert (`Artikel` ist von `Art.-Nr.` abhängig, `Art.-Nr.` ist jedoch kein Primärschlüssel)
![\1](attachments/\1)
![\1](attachments/\1)
![\1](attachments/\1)

## Quellen

> Redaktion, I. (2018). Weniger Redundanz dank Datenbank-Normalisierung. IONOS Digital Guide. Retrieved from https://www.ionos.de/digitalguide/hosting/hosting-technik/normalisierung-von-datenbanken