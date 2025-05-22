- Visualisierung von Zuständen eines endlichen Automaten
- Darstellung des Lebenszyklus einzelner Objekte

## Diagrammstruktur
- Jedes Diagramm hat:
  - **Anfangszustand**
  - **Endzustand**
  - Mindestens einen **Zwischenzustand**

## Zustände
- **Darstellung**: Rechtecke
- **Pseudozustände**:
  - **Startzustand**: 
    - Keine eingehende Transition
    - Exakt eine ausgehende Transition
  - **Endzustand**: 
    - Keine ausgehende Transition
    - Ende der Verhaltensabfolge
  - **Gabelung**: 
    - Aufspaltung in parallele Zustände
  - **Synchronisation**: 
    - Vereinigung mehrerer paralleler Zustände
  - **Kreuzung**: 
    - Knotenpunkt für mehrere Transitionen
  - **Entscheidung**: 
    - Alternative Transitionen basierend auf vorheriger Entscheidung
  - **Eintrittspunkt**: 
    - Zusammenfassung gleichartiger Transitionen in einen zusammengesetzten Zustand
  - **Austrittspunkt**: 
    - Zusammenfassung gleichartiger Transitionen aus einem zusammengesetzten Zustand
  - **Flache Historie**: 
    - Speicherung des letzten aktiven Unterzustands eines zusammengesetzten Zustands
  - **Tiefe Historie**: 
    - Speicherung des letzten aktiven Unterzustands aller Hierarchie-Ebenen eines zusammengesetzten Zustands

## Ereignisse
- Beschreiben Bedingungen für den Zustandwechsel:
  - **entry**: Automatisches Auslösen beim Eintritt in den Zustand
  - **exit**: Auslösen beim Verlassen des Zustands
  - **do**: Wiederholtes Auslösen, solange der Zustand nicht wechselt

## Transitionen
- Zustandsübergänge, ausgelöst durch Ereignisse
- **Innere Transitionen**: 
  - Nicht unbedingt Bestandteil des Diagramms
- **Äußere Transitionen**: 
  - Obligatorisch, Zustand wechselt

## Elemente
![\1](attachments/\1)

## Beispiele
![\1](attachments/\1)
![\1](attachments/\1)
![\1](attachments/\1)

## Quellen

> Redaktion, I. (2020). UML-Zustandsdiagramme: Folgen von Objektzuständen sichtbar machen. IONOS Digital Guide. Retrieved from https://www.ionos.de/digitalguide/websites/web-entwicklung/uml-zustandsdiagramm