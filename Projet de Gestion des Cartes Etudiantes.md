Projet de Gestion des Cartes Etudiantes

Description

Ce projet est un système automatisé basé sur Google Apps Script permettant de gérer les demandes, la vérification et la génération des cartes étudiantes pour plusieurs écoles. Il relie un formulaire d'inscription (ou une WebApp) à une base de données Google Sheets, stocke les fichiers sur Google Drive et génère les cartes via des modèles Google Slides.

Fonctionnalités principales

Collecte des donnees : Réception des informations des étudiants (photos, preuves d'inscription) et stockage structuré dans Google Sheets.

Gestion des fichiers : Création automatique de dossiers personnalisés dans Google Drive pour chaque étudiant.

Multi-écoles : Configuration dynamique permettant de gérer plusieurs établissements avec des modèles de cartes et des couleurs spécifiques.

Traitement des images : Sauvegarde des fichiers encodés en base64 vers Google Drive.

Installation automatisée : Script d'initialisation pour créer l'architecture des dossiers Drive et les onglets du tableur.

Technologies utilisées

Google Apps Script (JavaScript)

Google Sheets (Base de données)

Google Drive (Stockage des pièces jointes)

Google Slides (Modèles de cartes)

Installation et Utilisation

Créer un nouveau projet Google Apps Script.

Copier les fichiers config.gs, utils.gs et main.gs dans le projet.

Remplir les variables globales dans config.gs avec les ID de vos propres fichiers Google (Dossiers Drive, Templates Slides, etc.).

Exécuter la fonction installSystem() une seule fois pour générer l'architecture.

Déployer le script en tant qu'application Web (WebApp).