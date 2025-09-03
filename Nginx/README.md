# Nginx
Ce container est un serveur web
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- le fichier "default.conf" sous ./Config/default.conf
- le répertoire "Sites-enabled" sous ./Sites-enabled
- le répertoire "www" sous ./www

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
