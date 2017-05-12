# Enigma paradox
### jeu web en duo

Enigma paradox est un jeu d'énigme en coopération.
Le but est de résoudre le plus d'énigmes possible, pour déterminer quel binôme sera le meilleur.

![wireframe](https://img4.hostingpics.net/thumbs/mini_547563enigma.jpg "wireframe 1")

## REGLES

* L'utilisateur doit créer une partie avec un ami et choisir son rôle (l'assistant et l'assisté), pour réssoudre des énigmes à deux.
* L'assisté doit décrire ce qu'il voit et l'assistant agit en conséquence.
* L'assistant doit donner des informations à l'assisté selon ce qu'il lui a dit précédement.
* L'équipe a un chrono pour résoudre le maximum d'énigme, que seul l'assisté voit.
* La résolution d'une énigme donne un bonus de temps.

## TECHNOLOGIES

Jeu développé en **Javascript**, avec **Phaser** comme outil supplémentaire.
Le _board_ des meilleurs scores est enregistré sur un serveur web standard, avec **PHP** et une base de données **mySQL**