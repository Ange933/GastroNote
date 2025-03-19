# GastroNote 🍽️⭐  
Un site web où les utilisateurs peuvent ajouter des restaurants, laisser des avis et voir la note moyenne de chaque établissement.

## 🎯 Fonctionnalités
### Gestion des restaurants
- Un utilisateur peut ajouter un restaurant avec un nom, une adresse et une description.
- Liste des restaurants disponibles sur la page d’accueil.
- Détails d’un restaurant avec la moyenne des avis.

### Ajout d'avis
- Un utilisateur peut laisser un avis sur un restaurant (note sur 5 + commentaire).
- Calcul automatique de la moyenne des notes.

### Affichage des avis
- Liste des avis pour chaque restaurant.
- Date et auteur de l'avis affichés.

## 📌 Technologies utilisées
- **Symfony** (Backend)
- **Twig** (Frontend)
- **MySQL** (Base de données)
- **Doctrine** (ORM pour gérer la BDD)
- **Bootstrap** (optionnel, pour le design)

## 🚀 Installation
```bash
git clone https://github.com/ton-repo/gastronote.git
cd gastronote
composer install
symfony server:start
