# Projectly
This is a french MEAN application for manage projects. Projectly contain a kanban and a whiteboard in real time with websockets.

Projectly est une application MEAN (MongoDB, Express, AngularJS & NodeJS) pour manager vos projets agiles. Projectly contient un kanban revisité
et un tableau en temps réel avec les websockets

Vour pouvez accéder à une démo ici en vous connectant avec le compte root-root : [Démonstration de Projectly](https://21101201.users.info.unicaen.fr/board_front/)

Notez que ce projet n'est que le fruit d'un travail universitaire de quelques semaines, il subsiste plusieurs bugs mais comme je ne tiens pas encore à jours ce projet, je n'ai pas le temps de les corriger :). 

# Let's go to install it !

Au préalable, vous devez avoir MongoDB ainsi que NPM d'installé sur votre machine.
Clonez le dépôt. Il y a deux dossiers :

## board_back : Le serveur node
 Vous pourrez insaller les modules utilisés avec la commande
 
  ```npm install```
  
  Dans le fichier app.js à la ligne 17, à la racine du dossier, renseignez votre base de données NoSQL

  Lancez le serveur Node en tapant dans votre prompteur :
  ```node app.js```

## board_front : Le côté angular

Dans le fichier app.js à la ligne 3, dans le dossier js, renseignez l'url du serveur NodeJS :

```var serverUrl = "NODE_URL";```

Ouvrez le board front à l'aide d'un serveur web, en effet il est toujours préférable d'utiliser Angular avec un serveur web plutôt que directement depuis le fichier que l'on ouvre dans le navigateur.
Certaines erreurs de cross domaines peuvent apparaître le cas échéant.



