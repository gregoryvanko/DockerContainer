# Jellyfin
Ce conteneur est un Media System pour gérer des vidéos
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le répertoire "config" sous ./Config/config
- les répertoires "cache" sous ./Config/cache

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
