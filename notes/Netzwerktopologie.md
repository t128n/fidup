## Point-to-Point 
![\1](attachments/\1)
- einfache, direkte physikalische Verbindung
- beide Geräte können diese Verbindung für gegenseitige Kommunikation nutzen
- **Vorteile**
	- Hohe Übertragungsgeschwindigkeit
	- Einfache Implementierung und Wartung
	- Geringe Latenzzeit
- **Nachteile**
	- Begrenzte Reichweite
	- Hohe Kosten bei vielen Verbindungen
	- Ausfall eines Geräts unterbricht die Kommunikation

## Point-to-Multipoint
![\1](attachments/\1)
- mehrere Hosts durch zentrales System gespeist
- alle Hosts haben eine Leitung zum zentralen System
- **Vorteile**
	- Effiziente Nutzung der Ressourcen
	- Einfache Erweiterung durch Hinzufügen neuer Hosts
	- Zentrale Verwaltung und Kontrolle
- **Nachteile**
	- Zentrales System kann zum Flaschenhals werden
	- Ausfall des zentralen Systems führt zu Kommunikationsausfall
	- Höhere Komplexität in der Verkabelung

## Line / Chain / Linien-Topologie
![\1](attachments/\1)
- Leitung von Host zu Host werden verlegt
- **Vorteile**
	- Einfache Installation und Erweiterung
	- Geringe Kosten für Verkabelung
	- Gut für kleine Netzwerke
- **Nachteile**
	- Ausfall eines Hosts kann das gesamte Netzwerk beeinträchtigen
	- Begrenzte Anzahl von Hosts, die angeschlossen werden können
	- Schwierigkeiten bei der Fehlersuche

## Bus-Topologie
![\1](attachments/\1)
- Alle Geräte sind über ein gemeinsames Kabel verbunden
- **Vorteile**
	- Geringe Kosten für Verkabelung
	- Einfache Installation
	- Gut für kleine Netzwerke
- **Nachteile**
	- Ausfall des Hauptkabels führt zum Ausfall des gesamten Netzwerks
	- Begrenzte Anzahl von Geräten, die angeschlossen werden können
	- Schwierigkeiten bei der Fehlersuche

## Ring-Topologie
![\1](attachments/\1)
- Jedes Gerät ist mit zwei anderen Geräten verbunden, wodurch ein geschlossener Ring entsteht
- **Vorteile**
	- Datenübertragung in eine Richtung reduziert Kollisionen
	- Einfache Datenübertragung und -verwaltung
	- Vorhersehbare Leistung
- **Nachteile**
	- Ausfall eines Geräts kann das gesamte Netzwerk beeinträchtigen
	- Schwierige Fehlersuche
	- Höhere Kosten für Verkabelung

## Stern-Topologie
![\1](attachments/\1)
- Alle Geräte sind über ein zentrales Gerät (Switch oder Hub) verbunden
- **Vorteile**
	- Einfache Fehlersuche und Wartung
	- Ausfall eines Geräts beeinträchtigt nicht das gesamte Netzwerk
	- Hohe Leistung und Skalierbarkeit
- **Nachteile**
	- Abhängigkeit vom zentralen Gerät
	- Höhere Kosten für zentrale Geräte und Verkabelung
	- Komplexität bei der Verkabelung

## Baum-Topologie
![\1](attachments/\1)
- Kombination aus Stern- und Bus-Topologie, hierarchische Struktur
- **Vorteile**
	- Flexibel und erweiterbar
	- Gute Organisation der Netzwerkstruktur
	- Einfache Fehlersuche in Teilbereichen
- **Nachteile**
	- Komplexität in der Implementierung
	- Ausfall des Hauptkabels kann große Teile des Netzwerks beeinträchtigen
	- Höhere Kosten für Verkabelung und zentrale Geräte

## Mesh / Maschen-Topologie
![\1](attachments/\1)
- Jedes Gerät ist mit mehreren anderen Geräten verbunden
- **Vorteile**
	- Hohe Redundanz und Ausfallsicherheit
	- Daten können mehrere Wege nehmen, was die Leistung verbessert
	- Gute Skalierbarkeit
- **Nachteile**
	- Hohe Kosten für Verkabelung und Hardware
	- Komplexe Implementierung und Wartung
	- Schwierigkeiten bei der Fehlersuche
