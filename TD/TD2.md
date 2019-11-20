# TD2 C++ : Dynamisme

# Préambule

## Quelques bonnes habitudes à prendre lorsqu'on fait de la programmation informatique

Avant chaque écriture de programme (quel que soit le langage), il faut successivement :

1. Analyser le problème à résoudre
2. Proposer un algorithme / méthode permettant de résoudre le problème posé.
3. En déduire le programme associé.
4. Simuler l'exécution du programme avec des valeurs assez variées.
5. S'il y a des erreurs revenir au point (3), (2) ou (1).

Les points (1) et (2) doivent se dérouler loin du clavier car ils sont totalement indépendants de tout langage de programmation. Un problème bien compris est ensuite facile à transcrire dans un langage ou un autre !

# Gestion dynamique d'une « todo list ».

L'exercice consiste à créer différentes classes permettant de gérer une « todo list ». 

L'objectif de ce TD est de manipuler des notions importantes du C++, à savoir les références / pointeurs ainsi que l'allocation dynamique.

## Question 1 : Création des classes basiques Todo et Todolist

Il s'agit ici de concevoir les 2 classes basiques Todo représentant la tâche à mémoriser et Todolist représentant l'ensemble des taches.

La classe Todo comprendra le minimum d'informations nécessaires à l'application, à savoir un identifiant numérique, un titre, une description et un statut pour la tâche.

La classe Todolist comprendra aussi le minimum d'informations nécessaires à l'application, à savoir un tableau de tâches.

1. Ecrire le code des classes Todo et Todolist avec leurs constructeurs, leurs getters et es méthodes permettant d'afficher leurs données.
2. Ecrire une méthode de la classe Todolist permettant d'ajouter une nouvelle tâche dans la liste.
3. Ecrire une méthode de la classe Todolist permettant de modifier le statut une tâche de la liste.
4. Ecrire une méthode de la classe Todolist permettant de supprimer une tâche de la liste.