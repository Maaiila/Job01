## Docker Version
![docker--version](image/docker--version.png)
Affiche la version actuelle de Docker installée sur la machine.

---


## Docker Info 1
![dockerinfo1](image/dockerinfo1.png)
Détails sur l'installation de Docker

---

## Docker Info 2
![dockerinfo2](image/dockerinfo2.png)


---

## Docker Info 3
![dockerinfo3](image/dockerinfo3.png)


---

## Docker Info 4
![dockerinfo4](image/dockerinfo4.png)


---

## Docker Info 5
![dockerinfo5](image/dockerinfo5.png)


---

## Docker Info 6
![dockerinfo6](image/dockerinfo6.png)
Finalisation des informations détaillées.

---

## Docker Ps
![dockerPs](image/dockerPs.png)
Affiche la liste des conteneurs Docker actifs avec `docker ps`.

---

## Docker Images
![DockerImages](image/DockerImages.png)
Liste des images disponibles localement avec la commande `docker images`.

---

##  Docker Run
![DockerRun](image/DockerRun.png)
Capture d'écran qui  montre l'utilisation des arguments lors de la commande `docker run`.

---

## Docker Stop
![DockerStop](image/dockerstop.png)
Capture d'écran qui montre l'arret du conteneur welcome-to-docker.

---

## Docker Pull
![DockerPull](image/dockerPullImg.png)
Capture d'écran qui récupère une image du dockerhub.

---

## Docker Img
![DockerImg](image/dockerimg.png)
Capture d'écran qui affichent les images avec leur propriétés.

---

## Docker New Container
![DockerNewContainer](image/dockernewcontainer.png)
 Construction du nouvaeu container.

---

## supprimer un conteneur spécifique
docker rm <nom_du_conteneur>

## supprimer plusieurs conteneurs
docker rm $(docker ps -a -q)

## supprimer Tous les conteneurs arrêtés
docker container prune

## Forcer la suppression d'un conteneur actif
docker rm -f <nom_du_conteneur>

## supprimer Une image spécifique
docker rmi <nom_de_l_image>

## supprimer plusieurs images
docker rmi <nom_image_1> <nom_image_2> <nom_image_3>

## supprimer toutes les images inutilisées
docker image prune -a

## Forcer la suppression d'une image
docker rmi -f <nom_de_l_image>

## ERREUR
L'erreur est qu'il y a deux fois supprimer toutes les images non utilisés , la correction est images utilisés



