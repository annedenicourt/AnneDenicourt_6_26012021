# PROJET 6 OPENCLASSROOMS = "Construire une API sécurisée pour une application d'avis gastronomiques"

Ceci est le sixième projet OPENCLASSROOMS de Anne Denicourt

# Objectif du projet

Réaliser la partie backend puisque le frontend était déja fourni et création de l'API

## Piquante

La partie frontend a été générée avec [Angular CLI](https://github.com/angular/angular-cli) version 7.0.2.
La partie backend a été générée avec Node.js
Pour faire fonctionner le projet, vous devez installer node-sass à part.

## Development server

Frontend = démarrer `ng serve` pour avoir accès au serveur de développement. Rendez-vous sur `http://localhost:4200/`. L'application va se recharger automatiquement si vous modifiez un fichier source.
Backend = démarrer `node serve` ou 'nodemon server' pour avoir accès au serveur de développement. Rendez-vous sur `http://localhost:3000/`. L'application va se recharger automatiquement si vous modifiez un fichier source.


# Contraintes techniques

- Pratiques de code sécurisées
- Protéger les données utilisateurs (mot de passe chiffré)
- Respecter les standards OWASP et le RGPD
- Hébergement sur serveur Node.js
- Base de données MongoDB
- Framework Express
- Routes CRUD
- 2 types de droits administrateur à la base de données doivent être définis : un accès pour supprimer ou modifier des tables, et un accès pour éditer le contenu de la base de données
- Adresses mails de la base de données uniques
- Toutes les routes relatives à la sauce doivent exiger une demande authentifiée (contenant un jeton valide dans son en-tête d'autorisation : "Bearer <token>").



