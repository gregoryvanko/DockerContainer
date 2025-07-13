# Nginx
Serveur web de test
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- un volume externe Nas-Docker-Test : c'est une volume NFS sur un Nas
- enregister sur le Nas le fichier default.conf sous Nas-Docker-Test/Nginx1/Conf/default.conf
- créer un fichier index.html de test sur le Nas sous Nas-Docker-Test/Nginx1/Html/index.html
