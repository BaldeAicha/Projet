# 🎡 Système de Gestion de Jeux Concours & Logistique (Leclerc)

## 📝 Contexte du Projet
Conception d'une base de données relationnelle pour automatiser la gestion des jeux concours "Fidélité" d'une enseigne de grande distribution. Le système gère l'inscription via borne interactive et la logistique des lots (voyages tout compris) en collaboration avec des agences partenaires.

## 🏗️ Architecture de la Base de Données
Le modèle est conçu pour assurer l'intégrité des données entre le parcours client et la réservation des gains :

- **Pôle Client & Participation :** Tables `Client` et `Magasin`. Gestion de l'identification unique via le scan du ticket de caisse et de la carte de fidélité.
- **Pôle Récompense :** Tables `Voyage`, `Hotel`, `Lieu`. Centralisation des prestations "tout compris".
- **Pôle Partenaires :** Table `Agence`. Suivi des réservations et des prestataires de services à bas prix.

## 🛠️ Fonctionnalités SQL démontrées
- **Modélisation Relationnelle :** Mise en place de clés étrangères pour lier les participations aux lots.
- **Requêtes Décisionnelles :** Extraction de listes de gagnants et statistiques de participation par code postal.
- **Gestion Logistique :** Suivi des réservations de billets et d'hôtels liés à chaque jeu concours.

## 🚀 Exemple de requête (Analyse Business)
Le projet inclut des scripts permettant de vérifier le taux de remplissage des agences de voyage partenaires et la popularité des destinations proposées.

