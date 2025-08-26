# Cloudflare
Ce container permet de mettre en place une tunel CloudFlare vers une application web contenue dans un autre container.
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- le fichier .env avec sont contenu
## Variable d'environnement
|Variable|Definition|
|---|----|
|CLOUDFLARED_TOKEN|Token recu lors de la création du tunnel chez CloudFlare.|
