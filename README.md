# Enigma paradox
### Jeu web en duo

Enigma paradox est un jeu d'énigme en coopération.
Vous incarnez Sherlock Holmes et Watson, votre but est de résoudre le plus d'énigmes possible, pour déterminer qui seront les meilleurs detectives.

### Mise en situation du jeu :

![wireframe](https://img4.hostingpics.net/thumbs/mini_801136201705151053120.jpg "wireframe 1")

## REGLES

* L'utilisateur doit créer une partie en local avec un ami et choisir son rôle (Sherlock Holmes et Watson), pour réssoudre des énigmes à deux.
* Les joueurs sont sur 2 écrans différents pour ne pas visualiser l'écran de l'autre (cf l'image du dessus). 
* Sherlock Holmes doit décrire ce qu'il voit et Watson agit en conséquence.
* Watson doit donner des informations à Sherlock Holmes selon ce qu'il lui a dit précédement pour résoudre les énigmes.
* L'équipe a un chrono pour résoudre le maximum d'énigme, que seul Sherlock Holmes voit.
* La résolution d'une énigme donne un bonus de temps.
* Le records des 2 joueurs leurs est donner à la fin de leurs séries pour ce comparer aux autres joueurs.

## TECHNOLOGIES

Jeu développé en **Javascript**, avec **Phaser** comme outil supplémentaire.
Le _board_ des meilleurs scores est enregistré sur un serveur web standard, avec **PHP** et une base de données **mySQL**