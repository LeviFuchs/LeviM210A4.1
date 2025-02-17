# LeviM210A4.1
# Container-Orchestrierung – Fragen und Antworten

## Warum braucht man Container-Orchestrierung?
- Automatisierung von Deployment, Skalierung und Verwaltung vieler Container  
- Hohe Verfügbarkeit und Ausfallsicherheit sicherstellen  
- Ressourcen effizient nutzen  
- Netzwerk- und Speicherverwaltung für Container erleichtern  

## Wie funktioniert Container-Orchestrierung?
- Definiert und verwaltet Container-Deployments auf mehreren Hosts  
- Verteilt Workloads automatisch und sorgt für Lastenausgleich  
- Überwacht Container und startet sie neu bei Fehlern  
- Skaliert Container je nach Last automatisch hoch oder runter  
- Verwaltet Netzwerke und Volumes zwischen Containern  

## Welche Container-Orchestrierung Technologien kennen Sie?
- **Kubernetes**
- **Docker Swarm**
- **Apache Mesos**
- **Nomad (von HashiCorp)**

## Was versteht man unter "Scaling Containers"?
- Erhöhung oder Reduzierung der Anzahl laufender Container basierend auf der Last  
- Kann horizontal (mehr Instanzen) oder vertikal (mehr Ressourcen pro Container) erfolgen  
- Wird oft durch Orchestrierungs-Tools wie Kubernetes automatisiert  

## Was gibt es für Deployment Strategien?
- **Rolling Update** (schrittweises Update ohne Downtime)  
- **Blue-Green Deployment** (zwei Versionen parallel, Umschaltung nach Tests)  
- **Canary Deployment** (kleiner Teil der Nutzer bekommt neue Version zuerst)  
- **Recreate Deployment** (alte Container stoppen, neue starten)  
- **A/B Testing** (verschiedene Versionen für unterschiedliche Nutzergruppen)  
