Kind - Cluster

Zur Umsetzung unseres Projektes benötigen wir einen Cluster. 

Die Entscheidung fiel für Präsentationszwecke auf kind.

Vorraussetzung ist eine Container-Engine, dafür wurde Docker verwendet.

Installation von Docker

https://docs.docker.com/engine/install/ubuntu/

Installation von kubectl

https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-kubectl-binary-with-curl-on-linux

      curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
      
      sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl

Installation von kind

https://kind.sigs.k8s.io/docs/user/quick-start/#installation

Kind Cluster starten 

      kind create cluster
