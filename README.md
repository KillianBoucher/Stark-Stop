

# Stark&Stop

## Introduction

Stark&Stop est une plateforme en ligne de revente de véhicules de luxe, permettant aux clients et aux professionnels d'acheter et de vendre des voitures haut de gamme en France. Le site vise à offrir une expérience utilisateur fluide et agréable, en assurant une navigation facile et sécurisée.

## Technologies Utilisées

L'application est développée en utilisant PHP, HTML5 et CSS avec le framework Bootstrap pour le design. La base de données est gérée par phpMyAdmin et MySQL.

## Architecture de Navigation

- Accueil
- Vendre
- Services
- Conseils
- Annuaire des professionnels
- Publier une annonce gratuitement

## Fonctionnalités

### Inscription / Connexion

L'application permet aux utilisateurs de s'inscrire et de se connecter. Les utilisateurs peuvent s'inscrire en tant que particulier ou professionnel, fournissant des informations comme le nom, prénom, adresse email, mot de passe et le pays de résidence. Pour les professionnels, des informations supplémentaires comme le nom de l'entreprise, le SIRET et la TVA sont nécessaires.

### Consultation des Véhicules

Les utilisateurs peuvent consulter une liste de véhicules disponibles, triés par date de mise en ligne, marque ou modèle. Chaque véhicule a une fiche d'information détaillée incluant la marque, le modèle, la puissance fiscale, la puissance DIN, les équipements, etc. Les professionnels ont accès à plus d'informations que les particuliers, comme la date de mise en circulation du véhicule.

### Gestion des Véhicules

Les professionnels peuvent créer de nouvelles annonces de véhicules en remplissant un formulaire détaillé. Ils peuvent également mettre à jour les informations d'une annonce existante.

## Installation

Pour installer et exécuter cette application :

1. Clonez le dépôt
2. Installez les dépendances avec `composer install`
3. Copiez `.env.example` en `.env` et configurez votre environnement et les détails de la base de données
4. Exécutez `php artisan key:generate` pour générer une clé d'application
5. Exécutez `php artisan migrate` pour créer les tables de la base de données
6. Exécutez `php artisan serve` pour démarrer l'application

## Diagramme Cas d'Utilisation et Schéma BDD

Ces documents sont disponibles dans le dossier "docs" de ce dépôt.

## Contribution

Les contributions sont toujours les bienvenues. Veuillez lire la [contribution guide](CONTRIBUTING.md) pour plus d'informations.
