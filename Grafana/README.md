# Grafana
Ce conteneur permet de visualiser des dashboards
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le fichier "grafana.ini" sous ./Config/config/grafana.ini
- le répertoire "data" sous ./Config/data/
- le répertoire "log" sous ./Config/log/
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|GF_SECURITY_ADMIN_USER|Le user du compte admin|
|GF_SECURITY_ADMIN_PASSWORD|Le MP du compte admin|
