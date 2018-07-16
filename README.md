# LAMP en Docker

La technologie Docker permet au développeur de télécharger et installer un environnement de développement prêt à l'emploi, tout fait qui tournera en machine virtuelle sur ta machine, donc faisant cohabiter le serveur de développement dans l' OS du développeur sans devoir chipoter avec les permissions ou modifier les fichiers-systèmes de son ordinateur. Merci Docker, tu es le bien.

Pour voir ce qu'installe ce package-ci, lis le fichier docker-compose.yml.

## Préliminaire

1. Si vous êtes sur Mac ou Windows, veillez à d'abord installer Docker Desktop: https://docs.docker.com/install/ 
1. Installer Docker: https://www.docker.com/docker-ubuntu  
1. Installer Docker Compose : mpose/ins


## Utilisation

You are up and running in three simple steps:
```sh
// Cloner ce repository
$ git checkout $(git describe --abbrev=0 --tags)
$ cd docker-lamp 
$ docker-compose up --build -d 
```
Et voila!
