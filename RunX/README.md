# RunX
Ce conteneur permet de visualiser des dashboards de courses
## Installation
Avant de déployer le container, il faut créer:
- un reseau externe frontend
- le fichier .env avec sont contenu

Dans le fichier docker compose il faut changer:
- le nom du host traefik de la section labels
## Variable d'environnement
| Variable | Défaut | Rôle |
|---|---|---|
| `PORT` | `3000` | Port HTTP |
| `MONGODB_URI` | `mongodb://mongo:27017` | Serveur MongoDB |
| `MONGODB_DB` | `RunX` | Nom de la base |
| `ADMIN_LOGIN` / `ADMIN_PASSWORD` | — | Compte administrateur |
| `JWT_SECRET` | — | Secret de signature des jetons |
| `JWT_EXPIRES_IN` | `12h` | Durée de validité d'un jeton |
| `LOG_RETENTION_DAYS` | `90` | Purge automatique des logs (0 = jamais) |
| `TRUST_PROXY` | `false` | `true` derrière un reverse proxy (IP réelle dans les logs) |
