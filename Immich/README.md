# Immich
Ce conteneur permet de gérer une librairie de photos
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le répertoire "upload" sous ./Config/upload/
- le répertoire "model-cache" sous ./Config/model-cache/
- le répertoire "postgresql" sous ./Config/postgresql/
- le répertoire "data" sous ./Config/data
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|UPLOAD_LOCATION|Localisation de la librairie principale et de l'endroit ou le photos seront uploadées|
|DB_DATA_LOCATION|Localisation de la base de donnée|
|LEARNING_CACHE_LOCATION|Localisation de la cache du machine learning|
|IMMICH_VERSION|Version du serveur immich|
|DB_PASSWORD|Password de la DB|
|DB_USERNAME|Le UserName de la DB|
|DB_DATABASE|Le nom de la DB|
