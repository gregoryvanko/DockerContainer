# Prometheus
Ce conteneur est un outil de monitoring
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le fichier "prometheus.yaml" sous ./Config/config/prometheus.yaml
- le répertoire "data" sous ./Config/data/
Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
