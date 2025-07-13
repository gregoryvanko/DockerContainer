# Trafik
Conteneur qui sert de reverse proxy
## Installation
Avant de déployer le container, il faut créer :
- un reseau externe frontend
- un volume externe Nas-Docker-Test : c'est une volume NFS sur un Nas
- sur le NAS, enregister le fichier traefik.yaml sous Nas-Docker-Test/Traefik/traefik.yaml
## Variable d'environnement
CF_DNS_API_TOKEN : API Key CloudFlare pour changer une valeur du DNS afin de vérifier et créer le certificat TLS pour les routs HTTPS
