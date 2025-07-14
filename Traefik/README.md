# Traefik
Ce conteneur sert de reverse proxy
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le fichier "traefik.yaml" sous ./Config/traefik.yaml
- le répertoire "conf" sous ./Config/conf/
- les répertoires "certs" sous ./Config/certs/
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|CF_DNS_API_TOKEN|API Key CloudFlare pour changer une valeur du DNS afin de vérifier et créer le certificat TLS pour les routs HTTPS|
