 Développement Backend 
- Nom : MINKOULOU NGAMBIDA Andrea Lorry
- Matricule : 23V2393
- Filière : Informatique Niveau 2
- UE : INF222 

 Introduction

Ce projet a pour objectif de développer une API backend permettant de gérer un blog simple.
Il s’inscrit dans le cadre du développement web en utilisant la plateforme CleeRoute pour les recherches.

L’API permet d’effectuer les opérations suivantes 
-Créer
-Lire
-Modifier
-Supprimer informations sur des articles.

Dans le cadre de ce projet, la plateforme CleeRoute a été utilisée pour :

- Créer un compte utilisateur
- Définir un objectif d’apprentissage en développement backend
- Suivre un parcours structuré
- Consulter les modules de formation
- Réaliser des quiz pour évaluer la compréhension

Cette plateforme permet un apprentissage progressif et personnalisé.

Réalisation de l’API Backend Technologies utilisées

- Node.js
- Express
- MySQL
- Swagger
- Postman

  Dépendances utilisées :
- npm install
- nano server.js
- node server.js
- nano route/articles.js
- nano config/db.js
- node config/db.js
- node app.js
  
Base de données
Une base de données nommée article a été créée avec une table principale "articles".

Structure de la table :

- id (INT, clé primaire)
- title (VARCHAR)
- content (TEXT)
- author (VARCHAR)
- created_at (DATETIME)
- category (VARCHAR)
- tags (VARCHAR)
Fonctionnalités de l’API

L’API implémente les fonctionnalités suivantes :

- Création d’un article ("POST /api/articles")
-  Lecture de tous les articles 
-  Lecture d’un article par ID 
-  Modification d’un article
-  Suppression d’un article 
- Recherche d’articles

Les données sont retournées au format JSON.

La documentation a été réalisée avec Swagger et est accessible via :

http://localhost:3000/api-docs

Cette interface permet de tester directement les endpoints de l’API

Ces outils ont permis de vérifier le bon fonctionnement des routes et des réponses.

Analyse critique de CleeRoute

- Interface intuitive
- Parcours d’apprentissage structuré
- Présence de quiz interactifs

- Manque de profondeur sur certains concepts techniques
- Peu d’exemples pratiques avancés

Améliorations possibles

- Ajouter plus de projets pratiques
- Améliorer les explications techniques détaillées

 Conclusion

Ce projet m’a permis de comprendre :

- le fonctionnement d’une API backend
- la communication entre serveur et base de données
- l’utilisation de technologies modernes comme Node.js et Swagger

