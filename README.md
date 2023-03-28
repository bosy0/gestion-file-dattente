# Gestion de files d'attente

Le logiciel est un gestionnaire de files d’attente qui a plusieurs fonctionnalités. Le 
nombre de clients AINSI que le nombre de services sont infinis. Chaque client choisi le 
service qu’il demande. Chaque service à sa propre liste d’attente. Le guichetier n’a plus qu’à 
entrer le service qui demande un nouveau client et une interface Tkinter permet d’afficher le 
nom du client demandé ainsi que le service appelé.



### Structure du code :

Le code est divisé en deux parties : Premièrement, nous avons une classe qui tout d’abord 
initiale le dictionnaire. Elle est composée de trois méthodes :

- La première ajoute un client dans une liste d’attente du service demandé
- La seconde permet au guichetier de chercher le prochain client d’un service
- La troisième permet, s’il reste des clients dans la file d’attente demandée, d’afficher à 
l’aide de Tkinter le nom du client ainsi que le service associé.


Secondement, nous avons une fonction permettant de choisir une méthode de cette classe. 
Il y a trois possibilités possibles :

- n : Permet d’ajouter un client avec f.gererClient()
- s : Demande le service afin de lancer l’interface appelant le prochain client
- q : Quitter le programme à l’aide d’assert.

Si aucune des trois solutions est entrée, le logiciel relance cette fonction en rappelant les 
différentes actions
