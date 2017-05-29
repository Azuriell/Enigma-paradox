# Enigma paradox
### Jeu web en duo

Enigma paradox est un jeu d'énigme en coopération.
Vous incarnez Sherlock Holmes et Watson, votre but est de résoudre le plus d'énigmes possible, pour déterminer qui seront les meilleurs détectives.

### Mise en situation du jeu :

![wireframe](https://img4.hostingpics.net/thumbs/mini_801136201705151053120.jpg "wireframe 1")

### Rendu in game :

![wireframe](https://img15.hostingpics.net/thumbs/mini_154667Rendu1.png "wireframe 1")
![wireframe](https://img15.hostingpics.net/thumbs/mini_910824Rendu2.png "wireframe 1")
![wireframe](https://img15.hostingpics.net/thumbs/mini_201877Rendu3.png "wireframe 1")
![wireframe](https://img15.hostingpics.net/thumbs/mini_970315Rendu4.png "wireframe 1")


## REGLES

* L'utilisateur doit créer une partie en local avec un ami et choisir son rôle : Sherlock (le détective) ou Watson(l'assitant), pour résoudre des énigmes à deux.
* Les joueurs sont sur 2 écrans différents pour ne pas visualiser l'écran de l'autre. 
* Sherlock Holmes doit décrire ce qu'il voit et Watson agit en conséquence.
* Watson doit donner des informations à Sherlock Holmes selon ce qu'il lui a dit précédement pour résoudre les énigmes.
* L'équipe à un chrono pour résoudre le maximum d'énigme, que seul Sherlock Holmes voit.
* La résolution d'une énigme donne un bonus de temps.
* Le records des 2 joueurs leur est donné à la fin de leurs séries pour se comparer aux autres joueurs.

## TECHNOLOGIES

Jeu développé en **Javascript**.
Le _board_ des meilleurs scores est enregistré sur un serveur web standard, avec **PHP** et une base de données **mySQL**

## DATA

* 1 ère énigmes : Décryptage de texte (5 clé de decryptage).

* 2 ème énigmes : Simon says à deux (Ajout de règle différente pour pouvoir faire l'énigme à deux).

* 3 ème énigmes : Mini jeu d'asteroide invisible (Watson va devoir indiquer la position des asteroides pour que Sherlock les détruisent "Ca ne colle pas au thème, a modifier !").