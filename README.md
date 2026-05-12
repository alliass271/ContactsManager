# ContactsManager - Exercice de Programmation Orientée Objet (POO)

Ce projet est une application Java simple développée dans le cadre du cours "Le monde des objets". L'objectif est de mettre en pratique les concepts fondamentaux de la POO, notamment la création de classes, l'instanciation d'objets, l'utilisation de constructeurs et l'appel de méthodes.

## Objectifs de l'exercice

L'exercice consiste à :
1.  Créer un projet nommé **ContactsManager**.
2.  Définir une classe `Contact` avec des attributs pour le nom (`name`) et le numéro de téléphone (`phoneNumber`).
3.  Définir une classe `ContactsManager` capable de stocker une liste de contacts.
4.  Implémenter une méthode `addContact` pour ajouter des objets `Contact`.
5.  Implémenter une méthode `searchContact` pour retrouver un numéro de téléphone à partir d'un nom.

## Structure du Projet

Le projet se compose de trois parties principales :
- **`Contact.java`** : Définit la structure des données d'un contact.
- **`ContactsManager.java`** : Contient la logique de gestion (stockage, ajout et recherche).
- **`Main.java`** : Point d'entrée de l'application qui exécute les étapes demandées (création de 5 contacts et test de recherche).

## Instructions d'Exécution

Pour exécuter ce projet localement :

1.  Assurez-vous d'avoir le **JDK (Java Development Kit)** installé sur votre machine.
2.  Clonez ce dépôt :
    ```bash
    git clone https://github.com/[VOTRE_NOM_UTILISATEUR]/ContactsManager.git
    ```
3.  Compilez les fichiers Java :
    ```bash
    javac *.java
    ```
4.  Lancez l'application :
    ```bash
    java Main
    ```

## Fonctionnalités Implémentées

- [x] Création d'un objet `ContactsManager` via le constructeur par défaut.
- [x] Création et configuration de variables `Contact`.
- [x] Ajout de plusieurs contacts à la liste.
- [x] Recherche d'un contact par son nom et affichage de son numéro dans la console.

---
*Projet réalisé dans le cadre de la formation Pigier.*# ContactsManager
