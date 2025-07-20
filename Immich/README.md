# Immich
Ce conteneur permet de gérer une librairie de photos
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le répertoire "upload" sous ./Config/upload/
- les répertoires "model-cache" sous ./Config/model-cache/
- les répertoires "postgresql" sous ./Config/postgresql/
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|CF_DNS_API_TOKEN|API Key CloudFlare pour changer une valeur du DNS afin de vérifier et créer le certificat TLS pour les routs HTTPS|
