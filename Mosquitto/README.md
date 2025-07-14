# Mosquitto
Ce conteneur sert comme broker mqtt
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le répertoire "config" sous ./Config/config/
- le fichier "mosquitto.conf" sous ./Config/config/mosquitto.conf
- le fichier "mosquitto.password" sous ./Config/config/mosquitto.password
- les répertoires "data" sous ./Config/data/
- les répertoires "log" sous ./Config/log/

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
