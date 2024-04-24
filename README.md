# Cours Git & GitHub

Git est un logiciel de versioning, qui permet de gérer plus efficacement le développement d'une application.

## Les principes de Git

- Toujours versionner son code : Même pour les petit projet le versioning est indispensable.
- Travailler sur une branche : Le travail dans une app s'effectue toujours sur une branche dédiée à la fonctionnalité que l'on développe.
- Ne pas travailler sur la branche master : La branche master est la branche principale de l'app, elle doit rester propre et stable.
- Toujours tirer avant de code : `git pull` est indispensable pour récupérer les dernières modifications de la branche sur laquelle on travaille.
- Enregistrer avec un message clair : `git commit -m "message"` permet de sauvegarder les modifications effectuées. Prenez le soin de rédiger un message clair et concis.

## Les commandes de base

| Commande | Description |
| --- | --- |
| `git init` | Initialise un dépôt Git |
| `git clone` | Clone un dépôt Git |
| `git status` | Affiche l'état du dépôt |
| `git add` | Ajoute un fichier à l'index |
| `git commit` | Enregistre les modifications |
| `git remote` | Gère les dépôts distants |
| `git push` | Pousse les modifications sur le dépôt distant |
| `git pull` | Récupère les modifications du dépôt distant |
| `git branch` | Gère les branches |
| `git merge` | Fusionne les branches |

Il existe différente options (flags) pour chaque commande, en fonction de ce que l'on souhaite faire.

## GitHub

GitHub est un service en ligne qui permet d'héberger des projets Git. Il permet de partager son code, de travailler en collaboration et de gérer les problèmes (bugs, améliorations, etc.).

## Les principes de GitHub

- Priorité au dépôt local : GitHub est un service en ligne, il est donc important de toujours travailler en local et de pousser son code sur GitHub.
- Limiter les modifications directes sur GitHub : Les modifications directes sur GitHub sont à éviter, elles peuvent entraîner des conflits et des pertes de code.
- Sécuriser son compte : Activez la double authentification pour sécuriser votre compte et ainsi éviter les intrusions.
- Nommer des collaborateurs : Pour travailler en collaboration, il est important de nommer des collaborateurs sur un dépôt.
- Établisser des règles : Il est important de définir des règles de contribution pour que le travail en collaboration se passe bien.