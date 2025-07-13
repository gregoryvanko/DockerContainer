# Ubuntu
Serveur ubuntu pour editer les fichier sur le nas depuis une console dans portainer
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- un volume externe Nas-Docker-Test : c'est une volume NFS sur un Nas pour y enregister les fichiers des container docker
- un volume externe Nas-Data : c'est une volume NFS sur un Nas qui contient toutes les fichier du NAS
