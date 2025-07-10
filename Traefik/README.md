# Trafik
Conteneur qui sert de reverse proxy
## Configuration
Avant d'exécuter le container il faut créer un fichier de configuration avec le contenu du fichier traefik.yaml
```
mkdir /Docker/DockerConfig/Traefik
nano /DockerConfig/Traefik/traefik.yaml
```
## Variable d'environnement
CF_DNS_API_TOKEN : API Key CloudFlare pour changer une valeur du DNS afin de vérifier et créer le certificat TLS pour les routs HTTPS
