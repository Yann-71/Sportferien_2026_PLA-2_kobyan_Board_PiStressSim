# Projektübersicht

Dieses Projekt analysiert das Verhalten eines Webservers unter Normalbetrieb und unter kontrollierter, simulierter Überlast in einer vollständig abgesicherten Testumgebung. Ziel ist es, System- und Netzwerkreaktionen sichtbar, messbar und vergleichbar zu machen.

## Ziel des Projekts
Ich untersuche, wie sich eine erhöhte Anzahl von Anfragen auf einen Webserver auswirkt. Dabei liegt der Fokus auf Requests per Second (RPS), Netzwerktraffic und dem allgemeinen Systemverhalten – nicht auf der Zerstörung oder dem Abschalten des Systems.

## Umgebung
- Raspberry Pi als Webserver
- Kali Linux VM als Test- und Analyseumgebung
- Isoliertes Netzwerk
- Monitoring- und Analysewerkzeuge zur Traffic-Auswertung

## Vorgehen
Zuerst wird der Normalbetrieb gemessen. Anschliessend wird eine kontrollierte Last simuliert, um Unterschiede im Verhalten des Systems zu analysieren. Alle Tests erfolgen bewusst innerhalb definierter Sicherheitsgrenzen.

## Lernfokus
- Linux- und Netzwerkgrundlagen
- Verständnis von Webserver-Last und Traffic
- Praktische Systemanalyse und Monitoring
- Strukturierte, nachvollziehbare Arbeitsweise

