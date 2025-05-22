- **e**rweiterte **E**reignisgesteuerte **P**rozess**k**etten
- zur Modellierung von **[[Geschäftsprozess|Geschäftsprozessen]]** geeignet

## Regeln
1. Ein eEPK **beginnt und endet mit einem Ereignis.**
2. **Ereignisse und Funktionen wechseln** sich im Ablauf immer ab.
3. Sowohl Ereignis aus auch Funktion haben jeweils nur **einen Kontrollflußeingang** und **einen Kontrollflußausgang.**
4. Ein **Konnektor** kann **mehrere Kontrollflußeingänge** und **mehrere Kontrollflußausgänge** haben.
5. **Mehrere Teilabläufe** werden durch die **gleiche Art Konnektor** **zusammengeführt**, mit **der sie aufgeteilt** wurden.

## Elemente
![\1](attachments/\1)
- **Ereignis**, Start oder Ende eines Prozesses. Auslöser und Ergebnis von Funktionen
![\1](attachments/\1)
- **Funktion**, Elementarer Arbeitsschritt. Transformiert Input zu Output. Wird durch *Ereignis ausgelöst und hat Ereignis als Folge*
![\1](attachments/\1)
- **Oder-Konnektor** / **Operator**, teilt/verbindet Abfolge. Teilfolgen können *alternativ* oder auch *alle* durchlaufen werden
![\1](attachments/\1)
- **XOR-Konnektor** / **Operator**, teilt/verbindet Abfolge. Teilfolgen können nur *alternativ* durchlaufen werden
![\1](attachments/\1)
- **Und-Konnektor** / **Operator**, teilt/verbindet Abfolge. *Alle* Teilfolgen werden durchlaufen 
![\1](attachments/\1)
- **Kontrollfluss**, Verbindet Ereignisse und Funktionen sowie Konnektoren
![\1](attachments/\1)
- **Prozesswegweiser**, verweist auf kompletten *Teilprozess*, der separat modelliert ist
![\1](attachments/\1)
- **Organisationseinheit** / **Person**, Beteiligten an Funktion
![\1](attachments/\1)
- **Daten**, beschreibt welche Daten von einer Funktion *benötigt* oder *erzeugt* werden
![\1](attachments/\1)
- **Programm** / **Modul**, beschreibt mit welchem Modul/Programm die Funktion Daten transformiert
![\1](attachments/\1)
- **Anwendungssystem**, beschreibt mit welchem Anwendungssystem (mehreren Modulen, Programme, ...) die Funktion Daten transformiert

## Beispiele

![\1](attachments/\1)![\1](attachments/\1)