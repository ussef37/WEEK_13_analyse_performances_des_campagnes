# Optimisation et Analyse des Performances des Campagnes Marketing 📊

## 📌 Présentation du Projet
Ce projet a été réalisé dans le cadre d'un **Jury Blanc** pour le référentiel **Data Analyst**. L'objectif est de mesurer et de visualiser l'impact des campagnes marketing sur les ventes et le comportement des clients pour une entreprise fictive.

L'analyse couvre l'intégralité de la chaîne de valeur de la donnée : de l'exploration initiale en Python jusqu'à la création d'un dashboard décisionnel interactif sous Power BI.

## 🎯 Objectifs
* **EDA (Exploratory Data Analysis) :** Comprendre la distribution des données et identifier les tendances.
* **Analyses Statistiques :** Valider scientifiquement l'impact des campagnes via des tests d'hypothèses.
* **ETL & Préparation :** Transformer des données brutes en un modèle exploitable.
* **Data Visualization :** Concevoir un tableau de bord interactif axé sur la performance (ROI, conversion, segmentation).

## 🛠️ Technologies Utilisées
* **Python (Pandas, Matplotlib, Seaborn, Scipy) :** Nettoyage, exploration et tests statistiques.
* **Power Query :** Transformation des données (Unpivot, typage, nettoyage).
* **Power BI :** Modélisation de données (Star Schema) et création de rapports.
* **DAX (Data Analysis Expressions) :** Création de mesures calculées complexes.

## 📂 Structure des Fichiers
* `data.csv` : Dataset brut contenant les informations clients, transactions et campagnes.
* `dictionnaire.csv` : Documentation des variables du dataset.
* `Analyse_Exploratoire.ipynb` : Notebook Python contenant l'EDA et les tests statistiques.
* `Marketing_Performance_Dashboard.pbix` : Fichier Power BI final.

## 🚀 Étapes du Projet

### 1. Analyse Exploratoire des Données (Python)
* Analyse descriptive (moyenne, médiane, écart-type).
* Visualisation de la distribution des ventes (Histogrammes & Boxplots).
* Identification des valeurs manquantes et traitement des anomalies/doublons.
* Analyse du taux d'acceptation initial des campagnes.

### 2. Tests Statistiques
* **Impact sur les ventes :** Utilisation de **T-tests** ou **ANOVA** pour comparer les montants moyens d'achats entre les groupes ayant accepté/refusé les campagnes.
* **Corrélations :** Test du **Chi²** pour analyser la relation entre les variables catégorielles (ex: Pays vs Succès de la campagne).
* Interprétation des **p-values** pour confirmer la significativité des résultats.

### 3. Transformation des Données (Power Query)
* **Unpivoting :** Transformation des colonnes de campagnes et de produits en lignes pour faciliter l'analyse multidimensionnelle.
* **Nettoyage :** Renommage des colonnes et gestion des types de données.
* **Organisation :** Création de tables de faits et de dimensions.

### 4. Modélisation et DAX (Power BI)
* Mise en place des relations (Clé : ID Client).
* Création de mesures clés :
    * *Total des ventes par produit et campagne.*
    * *Taux de conversion des campagnes.*
    * *Nombre de clients uniques.*

### 5. Dashboard Interactif
Le rapport final permet de filtrer dynamiquement les données par :
* **Campagne :** Comparaison de la performance entre les différentes vagues marketing.
* **Produit :** Identification des catégories les plus rentables.
* **Plateforme :** Analyse des canaux d'achat (Web, Magasin, Catalogue).

## 📈 Résultats Clés (Exemples)
* Identification du profil type du client réactif aux campagnes.
* Mise en évidence du canal de vente le plus performant.
* Recommandations stratégiques sur l'allocation du budget marketing par produit.

---
**Auteur :** Omar Hitar  
**Date :** 06/04/2026  
**Rôle :** Data Analyst Junior