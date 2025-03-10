# Prédiction des Maladies d'Alzheimer avec le Machine Learning

## Description du Projet
Ce projet vise à analyser des données médicales et à développer un modèle de Machine Learning capable de prédire le risque de développement de la maladie d'Alzheimer chez un patient. Nous utiliserons des données anonymisées issues de différentes sources médicales pour identifier les principaux facteurs de risque et proposer une approche prédictive.

## Objectifs
- **Explorer et analyser** les données médicales relatives à la maladie d'Alzheimer.
- **Nettoyer et préparer** les données pour le Machine Learning.
- **Construire un modèle prédictif** permettant d'identifier les patients à risque.
- **Visualiser et interpréter** les résultats pour fournir des recommandations utiles.

## Données Utilisées
Les données utilisées sont stockées dans les fichiers suivants :
- `alzheimers_disease_data.csv` : Données brutes sur la maladie d'Alzheimer.
- `modified_alzheimers_disease_data.csv` : Données pré-traitées.

Les attributs des données incluent :
- **Données démographiques** (âge, sexe, antécédents familiaux, etc.).
- **Examens cognitifs** (score MMSE, tests neuropsychologiques).
- **Imagerie cérébrale** (IRM, PET scan, etc.).
- **Biomarqueurs sanguins** (protéines tau, bêta-amyloïde).

## Technologies Utilisées
- **Python** avec les bibliothèques : `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`.
- **Jupyter Notebook** pour l'analyse exploratoire (`projet_data_alzheimer.ipynb`).
- **Modèles de Machine Learning** : Random Forest, Régression Logistique, XGBoost, etc.

## Structure du Projet
- alzheimers_disease_data.csv  # Contient les données brutes
-  modified_alzheimers_disease_data.csv  # Contient les données traitées et modifiées
-  projet_data_alzheimer.ipynb  # Contient l'analyse exploratoire et les modèles prédictifs ( Random Forest, Régression Logistique, XGBoost, etc.)
-  README.md # Documentation du projet 


## Installation
1. Cloner le projet :
   ```bash
   git clone https://github.com/emmasvd2/data-IA-projet.git
   cd data-IA-projet
   ```
Lancer l'analyse exploratoire :
   ```bash
jupyter notebook projet_data_alzheimer.ipynb
```

## Auteurs
Léa BCHOUTY /
Emma STIEVENARD /
Chahinez MEZOUAR

