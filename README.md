# Phase 1 Projekt

## Präambel
0
Die Agenda dient als Leitfaden für das Projekt, bei dem ein Helm Chart für eine eigene Applikation mit API, Datenbank und webfrontend erstellt und auf einem Cluster ausgerollt werden soll. Darüber hinaus soll ein ausführliches Betriebshandbuch erstellt werden, das den kompletten Rollout und Betrieb der Software beschreibt. Die Agenda fasst die wichtigsten Schritte und Ziele des Projekts zusammen und dient als Orientierung für alle Beteiligten.

## Agenda

### Planung(JB):
- Klärung der Anforderungen an die Applikation und die Datenbank
  - SQL-Datenbank
  - API
  - webfrontend
  - Cluster
  - Container
- Auswahl der geeigneten Technologien
  - Meeting "Klärung der zur Auswahl stehenden Technologien"
- Erstellung eines technischen Konzepts
  - Visuelle Übersicht zur Kundenpräsentation
- Erstellung einer Projektstruktur
  - in Bearbeiteung
### Entwicklung(Mahad):
 Benötigten Komponenten: 
 - 4 config files: 
          -Configmap (DB Endpoint)
          -Secret ( DB User & pwd)
          -Deployment & service ( DB application mit internal servcie)
          -Deployment & Service ( eigene webapp mit external service)
          
- Implementierung der API
- Implementierung des webfrontends
- Implementierung der Datenbank
  - configmap.yaml und secret.yaml script anlegen
  -
### Erstellung des Helm Charts (Yasin):
- Definition der Templates und Konfigurationen
- Integration der bereits entwickelten Teile
### Dokumentation (JHG):
- [ ] Betriebshandbuch
  - [ ] Erstellung des Betriebshandbuchs
    - [ ] Struktur Betriebshandbuch aufsetzen
  - [ ] Pre-requisites abfragen und dokumentieren
- [ ] Dokumentation der Konfigurationen und Einstellungen
  - [ ] Konfigurationen abfragen
- [ ] Dokumentation der Deployment-Schritte
  - [ ] Deployment-Schritte abfragen
### Testen und Validierung (Behnur):
- Durchführung von Funktionstests
- Überprüfung der Skalierbarkeit
- Überprüfung der Zuverlässigkeit
### Deployment (Erik):
- Erstellung des Clusters
- Installation des Helm Charts auf dem Cluster
- Überprüfung der Funktionalität
### Betrieb:
- Überwachung des Clusters
- Fehlerbehebung
- Aktualisierungen
