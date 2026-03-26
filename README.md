# 🛒 Analyse de la Performance des Campagnes de Fidélité (Carrefour)

## 📌 Présentation
Ce projet simule la gestion technique et l'analyse d'une campagne de jeux concours "Fidélité". L'objectif est de structurer les données issues des bornes interactives en magasin pour piloter la stratégie marketing et logistique.

## ⚙️ Architecture SQL & Modélisation
Conception d'une base de données relationnelle optimisée pour le reporting :
- **Identification Client :** Liaison entre tickets de caisse et cartes de fidélité.
- **Logistique des Gains :** Gestion des dotations (voyages) via des agences partenaires.
- **Intégrité :** Utilisation de contraintes de clés pour garantir la fiabilité des données.

## 📊 Préparation au Reporting (BI)
La base est conçue pour alimenter un dashboard de pilotage permettant de suivre :
1. **Le Taux de Participation :** Analyse par zone géographique (Code Postal).
2. **La Performance des Agences :** Répartition des lots par partenaire.
3. **Le Profil des Gagnants :** Segmentation des clients ayant participé.

## 🛠️ Stack
- **Base de données :** SQL (PostgreSQL/MySQL)
- **Outils :** Modélisation Relationnelle, Requêtes d'Agrégation.
