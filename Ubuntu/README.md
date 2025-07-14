# Ubuntu
Serveur ubuntu pour editer les fichiers sur le nas
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- tous les volume externes existant sur le nas

Dans le fichier docker compose il faut:
- ajouter tous les volumes NFS créés par les autre containers. Les noms de ces volumes sont visibles dans Portainer
