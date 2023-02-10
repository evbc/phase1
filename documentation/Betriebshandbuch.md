# Betriebshandbung

## Pre-requisites

Folgende Dinge müssen vor Inbetriebnahme vorhanden sein:

 - (kind-) Cluster muss laufen
 - helm & kubectl müssen lokal vorhanden sein

## Weitere Informationen

Das Chart kann entweder bei z.B. [Artifacthub.io](https://artifacthub.io) geholt, oder aus dem Repo heruntergeladen und dann installiert werden.

Helm Chart installieren
```
helm install [NAME] [CHART] [OPTIONAL: -n (Namespace]
```

Mit folgenden Befehlen können können wir auf das Frontend zugreifen und die Datenbank verwenden.
