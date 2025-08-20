# Prometheus
Ce conteneur est un outil de monitoring
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le fichier "prometheus.yaml" sous ./Config/config/prometheus.yaml
- le répertoire "data" sous ./Config/data/

## Note
Traefik ne sera pas utiliser car il n'est pas nécessaire de pouvoir accéder à prometheus depuis le wan
