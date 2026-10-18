# Application de Gestion des Employés

Une application de bureau (Desktop) développée en Java (Swing) permettant de gérer de manière sécurisée et efficace le personnel d'une entreprise. Ce projet intègre un module d'authentification des utilisateurs ainsi qu'une interface complète de gestion des données (CRUD) connectée à une base de données relationnelle via JDBC.

## Aperçu de l'Application

1. Écran d'Authentification : Un accès sécurisé nécessitant un nom d'utilisateur et un mot de passe[cite: 6].
2. Tableau de Bord Principal : Une interface ergonomique affichant les statistiques, les formulaires de saisie et la liste des employés en temps réel[cite: 7].

## Fonctionnalités Principales

- Sécurité et Authentification : Connexion sécurisée avec contrôle d'accès utilisateur (ex: mode Administrateur)[cite: 6, 7].
- Gestion des Employés (CRUD) :
  - Ajouter : Enregistrement d'un nouvel employé avec ses informations détaillées (Matricule, Nom, Prénom, Poste, Salaire, Département, Date d'embauche)[cite: 7].
  - Modifier : Mise à jour des informations d'un employé existant[cite: 7].
  - Supprimer : Suppression d'un employé de la base de données[cite: 7].
  - Vider : Réinitialisation rapide des champs du formulaire[cite: 7].
- Recherche et Filtres : Barre de recherche dynamique permettant de filtrer rapidement les employés selon des critères spécifiques (ex : Matricule)[cite: 7].
- Affichage Tabulaire : Visualisation claire de l'ensemble des collaborateurs sous forme de tableau (`JTable`)[cite: 7].

## Technologies Utilisées

- Langage : Java (JDK 8 ou supérieur)
- Interface Graphique : Java Swing / AWT
- Accès aux Données : JDBC (Java Database Connectivity)
- Base de Données : MySQL / PostgreSQL (ou autre SGBD relationnel compatible)



