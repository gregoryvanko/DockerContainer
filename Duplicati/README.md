# Duplicati
Ce conteneur permet de faire des backup des répertoire Docker
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le répertoire "Config" sous ./Config
- le fichier .env avec sont contenu
- le répertoire "Backup" sur le Nas sous Nas-Proxmox/DockerBackup/NomVM

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
- l'adresse IP du nas dans la ligne "o: addr=192.168.10.23,rw,nolock" de la section Volumes => Nas-Proxmox
- le chemin du répertoire NFS dans la ligne "device: ":/var/nfs/shared/Proxmox/DockerBackup"" de la section Volumes =>  Nas-Proxmox
## Variable d'environnement
|Variable|Definition|
|---|----|
|ENCRYPTION_KEY|La clef d'encription de min 8 caractères|
|PASSWORD|Le MP pour accéder au site|
