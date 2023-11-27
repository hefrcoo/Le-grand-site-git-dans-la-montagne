
# Projet GIT
Voici le repositoire GIT, de notre projet de site pour notre cours de GIT



## Table des Matières

- [Projet GIT](#projet-git)
  - [Table des Matières](#table-des-matières)
  - [À Propos du Projet](#à-propos-du-projet)
  - [Fonctionnalités](#fonctionnalités)
  - [Structure du Site](#structure-du-site)
  - [Lien](#lien)
  - [Hook](#hook)

## À Propos du Projet

Il s'agit d'un site internet décrivant chacune des personne ayant travaillé sur ce projet.

## Fonctionnalités

Il est possible d'aller de page en page des différentes personnes via le header. Il est aussi possible d'accéder aux LinkedIn des personnes ayant travaillé sur le projet.

## Structure du Site

Donnez une vue d'ensemble de la structure de votre site. Par exemple :

- **Index** : La page d'accueil du site.
- **Page 1** : Description d'Adrien.
- **Page 2** :Je souhaite partager un projet open source fascinant : Lutris, un émulateur qui permet aux amateurs de jeux sur Linux, notamment ceux utilisant Ubuntu, de profiter de leurs titres préférés. L'objectif est d'offrir une expérience de jeu fluide sur cet OS, élargissant ainsi les possibilités de divertissement numérique sous Linux.
  ![screenshot](image/arthur.png)
- **Page 3** : Description de Mathias.
- **Page 4** : Description d'Hugo.

## Lien

Pas disponible pour le moment

## Hook

Voici le hook dans le prepare-commit-message:
```
#!/bin/bash

team_number="2"  # Remplacez X par le numéro de votre équipe
team_members=("AdrienG" "ArthurG" "MathiasH" "HugoC")  # Remplacez Y par les noms des membres de votre équipe

generate_commit_message() {
    echo "Nous sommes l'équipe ${team_number}, composée de ${team_members[*]}"
}

# Utiliser la fonction pour générer le message de commit
commit_message=$(generate_commit_message)

# Écrire le message de commit dans le fichier
echo "$commit_message" > "$1"
```
---

>>>>>>> prod
