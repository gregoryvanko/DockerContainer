# Influxdb
Ce conteneur est une base de donnees temporel
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le fichier "influx-configs" sous ./Config/config/influx-configs
- le répertoire "data" sous ./Config/data/
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|DOCKER_INFLUXDB_INIT_USERNAME|Le user du compte admin|
|DOCKER_INFLUXDB_INIT_PASSWORD|Le MP du compte admin|
|DOCKER_INFLUXDB_INIT_ORG|Le nom de l'organisation|
|DOCKER_INFLUXDB_INIT_BUCKET|Le nom du Bucket|
