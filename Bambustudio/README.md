# Bambustudio
Ce container permet d'utiliser Bambu Studio via une interface web.
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- un répertoire Config sous ./Config
- le fichier dockerfile avec son contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
