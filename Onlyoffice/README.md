# Onlyoffice
Ce conteneur permet de visualiser et de modifier des fichier office
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le répertoire "data" sous ./Config/data/
- le répertoire "db" sous ./Config/db/
- le répertoire "lib" sous ./Config/lib/
- le répertoire "logs" sous ./Config/logs/
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|JWT_SECRET|Le variable secrete du JWT|
