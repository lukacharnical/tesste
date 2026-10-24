# OpenStore — Dépôt complet mis à jour

Ce dossier contient l'ensemble des fichiers prêts à être extraits à la racine de ton dépôt GitHub.

## Fichiers inclus :
- `index.html` : Interface principale OpenStore avec chargement dynamique des thèmes/extensions et vérification des 3 administrateurs.
- `admin.html` : Panneau d'administration complet avec gestion des comptes, modération, notifications et logs.
- `config.json` : Fichier de configuration du thème global et des extensions personnalisées.
- `firebase.database.rules.json` : Règles de sécurité Firebase intégrant les 3 UIDs administrateurs (`Qo6URdVx5jMJ6KRAaQDezjDsQjH2`, `KfUNiHj3cRbLGIemZZRZP0e1sy02`, `S6zzNGq0swTfH4Og8RLaXUovH6Y2`).

## Instructions :
1. Télécharge et extrait l'archive ZIP.
2. Remplace l'ensemble des fichiers à la racine de ton dépôt GitHub.
3. Copie le contenu de `firebase.database.rules.json` dans l'onglet **Règles** de ta console Firebase Realtime Database.