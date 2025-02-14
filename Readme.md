# Docker

## Documentation

### variables d'environnement et arguments
- Documentation Dockerfile: https://docs.docker.com/reference/dockerfile/
- Docker compose reference: https://docs.docker.com/reference/compose-file/
- Tutoriel: https://vsupalov.com/docker-arg-env-variable-guide/

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


## K8s

install minikube:
https://minikube.sigs.k8s.io/docs/start

```
minikube start
```

### Commandes minikube
https://minikube.sigs.k8s.io/docs/commands/
- node, ip
- start, stop, status, pause
- service, tunnel
- logs, ssh
- mount, cp
- image
- dashboard: web GUI
- kubectl

### Commandes kubectl
https://kubernetes.io/docs/reference/kubectl/

- get pod(s) | deployment(s) | service | rs
- label: gestion des labels
https://kubernetes.io/docs/reference/kubectl/generated/kubectl_label/

## Movie API
https://github.com/matthcol/dockerkbs2025/releases

3 versions: 1.0, 1.1, 2.0

