# E-Banking Web Application

## Description
Ce projet a pour objectif la création d'une application web de gestion bancaire intitulée "E-banking web application". Cette application est conçue pour faciliter la gestion des comptes bancaires et des opérations associées, en mettant l'accent sur la sécurité et l'efficacité.

## Structure du Projet

### Entités Principales
Le projet se base sur cinq entités principales :
1. **BankAccount** : Représente un compte bancaire générique.
2. **CurrentAccount** : Spécifie un compte courant avec des caractéristiques spécifiques.
3. **SavingAccount** : Spécifie un compte d'épargne avec des caractéristiques spécifiques.
4. **Customer** : Représente les clients de la banque.
5. **Operation** : Représente les différentes opérations bancaires effectuées (dépôts, retraits, transferts, etc.).

### Partie Back-End

Pour le back-end, nous avons choisi d'utiliser Spring Boot, un framework puissant et flexible pour la création d'applications Java. Voici les principaux aspects de notre implémentation back-end :

1. **API REST** :
    - **Gestion des Comptes Bancaires** : Cette API permet la lecture des comptes bancaires, ainsi que la consultation de l'historique.
    - **Gestion des Clients** : Cette API permet de gérer les informations des clients, incluant la création de nouveaux clients, la modification de leurs informations, la recherche de clients par différents critères, et la suppression de clients.

2. **Sécurité** :
    - Nous avons intégré la sécurité dans notre application en utilisant des tokens JWT (JSON Web Tokens). Cette méthode permet d'assurer que seules les personnes autorisées peuvent accéder aux fonctionnalités sensibles de l'application.

### Partie Front-End

Pour le front-end, nous avons choisi Angular, un framework populaire pour le développement d'applications web interactives et dynamiques. Angular nous permet de créer une interface utilisateur réactive et intuitive, facilitant ainsi l'interaction avec l'application.

Voici quelques captures d'écran illustrant les différentes vues de notre projet :
- ![img 1](/img/login.PNG) Vue de la page de connexion sécurisée.
- ![img 2](/img/clients.PNG)  Tableau de bord montrant les clients.
- ![img 3](/img/ajout.PNG)  Interface d'ajout des clients.
- ![img 4](/img/Supprimer.PNG)  Supprimer un client.
- ![img 5](/img/Search.PNG)  Operation de recherche d'un compte.


## Installation

### Prérequis
- Java 11 ou supérieur
- Node.js et npm
- Angular CLI
- IDE (IntelliJ, VSCode, etc.)


## Utilisation

- Ouvrir un navigateur et accéder à `http://localhost:4200` pour utiliser l'application.

## Contribuer

Les contributions sont les bienvenues ! Veuillez soumettre des pull requests et ouvrir des issues pour tout problème rencontré ou suggestion d'amélioration.

