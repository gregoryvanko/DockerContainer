# MONGO
Ce container permet de créer une base de donnée mongo et une Web App permettant de visualiser cette base de donnée
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- un répertoire Data/db sous ./Data/db
- un répertoire Data/configdb sous ./Data/configdb
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
|Variable|Definition|
|---|----|
|MONGO_EXPRESS_USERNAME|Le username pour la Web App Mongo-Express|
|MONGO_EXPRESS_PASSWORD|Le password pour la Web App Mongo-Express|
