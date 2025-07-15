# Nginx
Ce container est un serveur web de test
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- le fichier "default.conf" sous ./Config/default.conf
- le fichier index.html de test sur le Nas sous Nas-Docker/Test/Nginx/Html/index.html

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
- l'adresse IP du nas dans la ligne "o: addr=192.168.10.23,rw,nolock" de la section Volumes => Nas-Docker-Test-Nginx
- le chemin du répertoire NFS dans la ligne "device: ":/var/nfs/shared/Docker/Test/Nginx/Html"" de la section Volumes => Nas-Docker-Test-Nginx
- le nom "Nas-Docker-Test-Nginx" dans les deux sections Volumes (pour la section services et pour la section volumes externe)
