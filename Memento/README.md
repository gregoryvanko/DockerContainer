# Memento
Ce container est une application web de blog
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- le répertoire "Nginx/www/Icon" sous ./Nginx/www/Icon
- le fichier "index.html" sous ./Nginx/www/index.html
- le fichier "IconBrown.png" sous ./Nginix/www/Icon/IconBrown.png
- le répertoire "Nginx/Sites-enabled" sous ./Nginx/Sites-enabled
- le fichier "default.conf" sous ./Nginx/Sites-enabled/default.conf
- le fichier "Memento.vanko.be.conf" sous ./Nginx/Sites-enabled/Memento.vanko.be.conf
- le répertoire "Nginx/Log" sous ./Nginx/Log

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
