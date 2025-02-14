# Formation WordPress

## 1. Installation des prérecquis
- Installer docker 
- Installer docker-compose
- Télécharger le dossier via le lien GitLab: https://github.com/jc-aziaha/start_wordpress_with_docker
    - Ce dossier contient le fichier de configuration de docker permettant d'installer WordPress
- Ouvrir le dossier dans un terminal de la machine
- Exécuter la commande "docker-compose up" pour installer:
    - WordPress 
        - Le serveur Apache
        - Le code source de Php
        - Le code source de WordPress en php
    - MySQL (SQL)
    - PhpMyadmin (Interface permettant de simplifier l'utilisation de MySQL)

## 2. Accès à l'interface de WordPress et celle de la base de données
- Se rendre dans le navigateur 
    - Dans un nouvel onglet, entrer l'url: http://localhost:8000 pour accéder à WordPress
    - Dans un nouvel onglet, entrer l'url: http://localhost:8080 pour accéder à la base de données

## 3. Configuration de WordPress
- Choix de la langue
- Insertion des informations necessaires concernant le site à créer
- Se connecter avec ses identifiants
- Une fois l'installation de WordPress réussie, les tables sont automatiquement crées dans la base de données

## 4. Exploration de l'espace d'administration de WordPress
- Présenter le dashbord
    - Présenter les fonctionnalités de la Sidebar
    - Présenter les fonctionnalités de la Navbar
    - Présenter les ressources proposées par WordPress
- Présenter l'apparence actuelle du site
- Modifier le thème de base proposé par WordPress
- Présenter les avantages des thèmes de base
    - Minimaliste
    - Permet d'aller vite
    - Permet de rapidement mettre en place, une solution
- Présenter les limites des thèmes de base
    - Minimaliste donc offre peu de fonctionnalités
    - Pas toujours beaux
    - Pas toujours compatibles avec les extensions avancés
    - Difficilement personnalisable de manière avancée
- Modifier le permalien
    - Reglage > Permalien
- Supprimer
    - toutes les pages
    - tous les articles et ses commentaires
    - toutes les extensions prévues par défaut