# Tableau de Bord de Fiabilité des Dispositifs Médicaux — Projet Power BI

## 📌 1. Résumé Exécutif

Ce projet analyse la fiabilité, le comportement de maintenance et l’impact opérationnel des dispositifs médicaux provenant de différents fabricants et catégories d’appareils.  
Le tableau de bord Power BI met en évidence les tendances de pannes, le temps d’indisponibilité, les coûts de maintenance et les schémas d’intervention, afin de soutenir la prise de décision dans la gestion d’actifs hospitaliers.

Les résultats révèlent des catégories d’équipements à risque élevé, des postes de coûts majeurs, ainsi que des opportunités d’amélioration des stratégies de maintenance préventive.

(INSÉRER SCREENSHOT PAGE 1 ICI)

---

## 📊 2. Description du Jeu de Données

**Source** : Kaggle – Medical Device Failure Dataset (anonymisé)  
**Nombre de lignes** : 8 123  
**Principales colonnes :**  
- Device Type (Type d’appareil)  
- Manufacturer (Fabricant)  
- Failure Event Count (Nombre de pannes)  
- Downtime (heures d’indisponibilité)  
- Maintenance Frequency (interventions annuelles de maintenance)  
- Maintenance Cost (coût annuel en USD)  
- Purchase Date  
- Maintenance Class (1–3)  
- Country  

Le dataset représente des historiques anonymisés de pannes et de maintenance pour des dispositifs médicaux.

---

## 📈 3. Tableau de Bord « Executive Summary » — Indicateurs Clés

Cette page présente une synthèse globale des performances opérationnelles :

- **Coût total de maintenance :** 35,9M USD  
- **MTTR (Mean Time To Repair) :** 11 heures  
- **Temps total d’indisponibilité :** 44 000 heures  
- **Nombre total de pannes :** 8 000 événements  

**Visuels inclus :**  
- Nombre de pannes par type d’appareil  
- Temps d’indisponibilité total par fabricant  

Ces visuels permettent d’identifier les catégories d’équipements et les fabricants qui génèrent le plus d’impact opérationnel.

(INSÉRER SCREENSHOT VISUELS PAGE 1 ICI)

---

## 🔍 4. Analyse des Pannes (« Failure Analysis »)

Cette page se concentre sur l’analyse du comportement des pannes.

**Principaux constats :**

- **Tendance annuelle des pannes :** fluctuations visibles, avec une baisse notable en 2024  
- **Pannes par pays :** des écarts importants entre régions, possiblement liés aux conditions d’utilisation ou aux processus  
- **Pannes par classe de maintenance :** les classes 1 et 2 représentent la majorité des événements  

Un tableau détaillé liste les appareils à risque :

- Device ID  
- Type d’appareil  
- Fabricant  
- Nombre de pannes  
- Temps d’indisponibilité  
- Coût de maintenance  

Cette table permet de cibler les actifs prioritaires pour des actions correctives.

(INSÉRER SCREENSHOT PAGE 2 ICI)

---

## 🛠️ 5. Tableau de Bord « Maintenance Workflow »

Cette page met l’accent sur les opérations de maintenance et les coûts associés.

**Visuels inclus :**
- Fréquence moyenne de maintenance par type d’appareil  
- Coût de maintenance par fabricant  
- Temps d’indisponibilité par type d’appareil  

**Tableau récapitulatif :**  
Affiche, pour chaque appareil :

- Nombre de pannes  
- Fréquence de maintenance  
- Coût de maintenance  
- Temps d’indisponibilité  

Cette vue permet d’identifier :
- Les fabricants les plus coûteux  
- Les appareils les plus perturbateurs  
- Les modèles nécessitant un entretien plus intensif

(INSÉRER SCREENSHOT PAGE 3 ICI)

---

## 🧭 6. Recommandations Métiers

- **Renforcer la maintenance préventive** pour les appareils présentant une fréquence élevée et un downtime important.  
- **Réévaluer les fournisseurs** dont les équipements présentent des coûts ou des indisponibilités anormalement élevés.  
- **Analyser les écarts géographiques** pour comprendre l’origine des variations de pannes (procédures, formation, environnement).  
- **Prioriser le remplacement des appareils** à fort coût total de possession.  
- **Optimiser les plannings de maintenance** en fonction des tendances observées.

---

## ⚠️ 7. Limites & Pistes d’Amélioration

**Limites :**
- Le dataset ne contient pas l’âge des appareils, leurs heures d’utilisation, ni la distinction entre maintenance préventive et corrective.  
- Certains outliers peuvent représenter des erreurs de saisie ou des cas très exceptionnels.

**Pistes d’amélioration :**
- Intégrer le MTBF (Mean Time Between Failures) et des modèles prédictifs.  
- Ajouter des indicateurs SLA pour évaluer les performances des techniciens.  
- Connecter le dashboard à des sources opérationnelles réelles (SQL, Smartsheet, API).  
- Mettre en place une actualisation automatique du rapport.

---

## 👤 Auteur

**Marouan Mehdi Belkaaloul**  
Data Analysis Enthusiast
