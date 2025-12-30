# poverty — Package R pour l’analyse de la pauvreté et des inégalités

## 📖 Présentation

**poverty** est un package R dédié à l’analyse quantitative de la pauvreté et des inégalités, ainsi qu’à l’évaluation de l’impact des politiques de transferts monétaires.  
Il automatise le calcul des principaux indicateurs socio-économiques et génère des **tableaux et graphiques prêts à l’emploi**, exportés dans des **fichiers Excel structurés par feuille**.

Ce package s’adresse aux **analystes, chercheurs, institutions publiques et ONG** travaillant sur les politiques de lutte contre la pauvreté.


## 🎯 Objectifs du package

- Automatiser le calcul des indicateurs standards de pauvreté et d’inégalités  
- Évaluer l’impact des **transferts monétaires** sur la pauvreté et la distribution du bien-être  
- Générer automatiquement des **tableaux statistiques** et des **visualisations**  
- Faciliter l’analyse **par sous-groupes** (sexe, région, milieu de résidence, etc.)  
- Produire des résultats exploitables directement dans **Excel**


## 🧩 Fonctions principales

### 🔹 Analyse descriptive de la population
- **`population_distribution()`**  
  Analyse la répartition de la population selon une ou plusieurs variables (sexe, âge, région, etc.).


### 🔹 Analyse de la pauvreté
- **`poverty_summary()`**  
  Calcule les indicateurs de pauvreté :
  - Taux de pauvreté (*Headcount Ratio*)
  - Écart de pauvreté (*Poverty Gap*)
  - Sévérité de la pauvreté (*Squared Poverty Gap*)
  - Répartition de la pauvreté par groupe


### 🔹 Analyse des inégalités
- **`inequality_indices()`**  
  Produit les principaux indicateurs d’inégalités :
  - Courbe de Lorenz
  - Indice de Gini
  - Indice de Theil


### 🔹 Simulation de politiques publiques
- **`transfers_summary()`**  
  Évalue l’impact de transferts monétaires sur :
  - La réduction de la pauvreté
  - Les changements dans les inégalités


### 🔹 Rapport automatique
- **`generate_full_report()`**  
  Génère un **rapport Excel complet** regroupant :
  - Les tableaux statistiques
  - Les graphiques
  - Les analyses par sous-groupes


## 📊 Sorties et visualisations

- Chaque fonction :
  - Retourne un **objet R structuré**
  - Génère des **tableaux formatés**
  - Produit des **graphiques** associés
- Les résultats sont exportés dans un **fichier Excel multi-feuilles**, avec :
  - Une feuille par analyse
  - Une structure standardisée facilitant l’interprétation


## ⚙️ Caractéristiques techniques

- **Données d’entrée requises** :
  - Variable de consommation ou de dépenses
  - Variable de poids
  - Variable de seuil de pauvreté
- **Analyse par sous-groupes** :
  - Via l’argument `separateur` (sexe, région, milieu, etc.)
- **Formats d’export** :
  - Excel (`openxlsx`)
- **Compatibilité** :
  - Bases EHCVM et autres enquêtes socio-économiques harmonisées


## 📌 Statut du projet

- 🔧 Fonctions en cours de développement et de validation  
- 🧪 Tests progressifs sur données réelles  
- 📦 Packaging CRAN prévu après stabilisation des fonctions


## 🛠️ Perspectives

- Ajout de nouvelles simulations de politiques publiques  
- Extension aux analyses dynamiques et comparaisons temporelles  
- Intégration d’exports graphiques avancés  
- Documentation et vignettes détaillées
