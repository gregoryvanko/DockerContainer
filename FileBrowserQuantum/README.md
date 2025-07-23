# FileBrowser Quantum
Ce conteneur sert est un Web File Browser
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le fichier "config.yaml" sous ./Config/config.yaml
- le répertoire "tmp" sous ./Config/tmp/
- le répertoire "Data" sur le Nas sous Nas-Docker-Data

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
- l'adresse IP du nas dans la ligne "o: addr=192.168.10.23,rw,nolock" de la section Volumes => Nas-Docker-Data
- le chemin du répertoire NFS dans la ligne "device: ":/var/nfs/shared/Data"" de la section Volumes => Nas-Docker-Data
