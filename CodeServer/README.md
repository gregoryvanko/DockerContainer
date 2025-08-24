# CodeServer
Ce container d'utiliser Visual Studio Code dans un browser
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- un répertoire Config sous ./Config
- un répertoire Projets sous ./Projets
- le fichier .env avec sont contenu
- le fichier dockerfile avec son contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|PASSWORD|Le password pour ouvrir Visual studio|
|SUDO_PASSWORD|Le password SUDO pour le terminal|
|PROXY_DOMAIN|Le nom de domain pour le proxy des ports ouverts via le code d'une application|
