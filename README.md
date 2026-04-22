# 🛒 Carrefour Voyages : Analyse de Performance & Stratégie de Fidélisation

## 📌 Présentation du Projet
Ce projet simule la gestion technique et l'analyse d'une campagne nationale de jeux-concours pour **Carrefour Voyages**. L'objectif est de structurer les données issues des bornes interactives en magasin pour piloter la stratégie marketing et optimiser les réservations de séjours.
## ⚙️ Architecture SQL & Modélisation
Conception d'une base de données relationnelle robuste, optimisée pour le reporting (BI) :
* **Référentiels Métiers :** Gestion centralisée des clients, des agences physiques et du catalogue hôtelier.
* **Flux de Réservations :** Liaison dynamique entre les profils clients et les prestations de voyages.
* **Sécurisation (Data Quality) :** Mise en place de contraintes strictes (`CHECK`, `REGEXP`) pour valider les emails, téléphones, et la cohérence des prix/dates.
* **Simulation de Production :** Automatisation via **procédures stockées** pour générer un volume de **1500+ lignes**, garantissant une analyse statistique représentative.

## 🎯 Problématique Business
> **"Comment transformer l'engagement ludique en magasin en réservations réelles et identifier les leviers de conversion les plus efficaces ?"**

## 📊 Préparation au Reporting (BI)
La structure permet d'alimenter des tableaux de bord pour suivre :
1. **Le Taux de Participation :** Analyse de l'engagement par zone géographique (Codes Postaux).
2. **La Performance des Agences :** Classement des points de vente les plus performants en conversion.
3. **Le Profil des Gagnants :** Segmentation des clients (habitudes de consommation, scores aux jeux).
4. **Analyse Produit :** Top destinations et types d'hôtels (standing) les plus réservés.

## 🛠️ Stack Technique
* **Base de données :** MySQL / MariaDB.
* **Langage :** SQL Avancé (Jointures complexes, Agrégations, Procédures stockées, Expressions régulières).
* **Méthodologie :** Modélisation Entité-Relation (Merise), Data Engineering (Génération de jeux de données).

---

### 📂 Structure du Dépôt
* `/scripts/01_creation_table.sql` : Schéma de la base et contraintes d'intégrité.
* `/scripts/02_insertion_data.sql` : Échantillons réels et scripts de génération massive.
* `/scripts/03_analyses_kpi.sql` : Requêtes d'extraction pour le reporting.
