# Phase 1 Projekt

## Präambel
0
Die Agenda dient als Leitfaden für das Projekt, bei dem ein Helm Chart für eine eigene Applikation mit API, Datenbank und webfrontend erstellt und auf einem Cluster ausgerollt werden soll. Darüber hinaus soll ein ausführliches Betriebshandbuch erstellt werden, das den kompletten Rollout und Betrieb der Software beschreibt. Die Agenda fasst die wichtigsten Schritte und Ziele des Projekts zusammen und dient als Orientierung für alle Beteiligten.

## Agenda

### Planung:
- Klärung der Anforderungen an die Applikation und die Datenbank
  - SQL-Datenbank
  - API
  - webfrontend
  - Cluster
  - Container
- Auswahl der geeigneten Technologien
  - Meeting "Klärung der zur Auswahl stehenden Technologien"
  - Termin: 13.02.23 von 13 - 16 Uhr Kundenworkshop
- Erstellung eines technischen Konzepts
  - Visuelle Übersicht zur Kundenpräsentation
- Erstellung einer Projektstruktur
  - in Bearbeiteung

### Entwicklung:        
- Implementierung der API
- Implementierung des webfrontends
- Implementierung der Datenbank
### Erstellung des Helm Charts:
- Definition der Templates und Konfigurationen
- Integration der bereits entwickelten Teile
### Dokumentation:
- [ ] Betriebshandbuch
  - [ ] Erstellung des Betriebshandbuchs
    - [ ] Struktur Betriebshandbuch aufsetzen
  - [ ] Pre-requisites abfragen und dokumentieren
- [ ] Dokumentation der Konfigurationen und Einstellungen
  - [ ] Konfigurationen abfragen
- [ ] Dokumentation der Deployment-Schritte
  - [ ] Deployment-Schritte abfragen
### Testen und Validierung:
- Durchführung von Funktionstests
- Überprüfung der Skalierbarkeit
- Überprüfung der Zuverlässigkeit
### Deployment:
- Erstellung des Clusters
  1. Auswahl des Kuberneres Clusters
    - Überblick über verschiedene Kubernetes Environments sammeln
    - Anforderungen beachten
    - Auswahl des Systems in Beachtung der Anforderungen 
  2. Installation des Clusters 
    - Installationsguide anschauen 
    - Quickstart durchführen 
  3. Erstes Projekt erstellen
  - Ergebnis Kubernetes Cluster (https://github.com/k3s-io/k3s) 
- Installation des Helm Charts auf dem Cluster
- Überprüfung der Funktionalität
### Betrieb:
- Überwachung des Clusters
- Fehlerbehebung
- Aktualisierungen
