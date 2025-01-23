# Docker

## Documentation

### variables d'environnement et arguments
Documentation Dockerfile: https://docs.docker.com/reference/dockerfile/
Tutoriel: https://vsupalov.com/docker-arg-env-variable-guide/

## Commandes principales
- ps: lister les conteneurs qui tournent ou inertes
- pull: télécharger une image
- run: créer et lancer un conteneur
- start/stop/restart: démarrer et arrêter un conteneur
- rm: supprimer un conteneur
- logs: voir les logs
- exec: exécuter une commande à l'intérieur du conteneur
- image(s)/rmi: gérer les images
- network: gérer les réseaux
- volume: gérer les volumes (disques virtuels)
- build: construire une image
- compose: gérer une composition
- cp: copier des fichiers entre conteneur(s) et/ou hôte
- stats: utilisation des ressources
- attach: attacher les flux standards à un conteneur
- search: chercher une image
- etc...

## Examples
```
docker run hello-world
docker ps # no result
docker ps -a # angry_archimedes
docker rm angry_archimedes
```

```
docker run --name hello hello-world
docker rm hello
```

### Remove all containers
docker rm -v -f 
