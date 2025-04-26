# Impact des CAP sur le Dépistage du VIH

## Description

Ce projet vise à analyser les connaissances, attitudes et pratiques (**CAP**) en lien avec le **dépistage du VIH** au sein d'une population cible.  
L'objectif est de :
- Décrire les niveaux de connaissance, attitude et pratique liés au VIH/sida.
- Identifier les facteurs associés au recours au **dépistage du VIH**.
- Évaluer la performance prédictive d'un modèle statistique pour le recours au test VIH.

## Données utilisées

- **Source** : Enquête démographique et de santé Cameroun (EDS 2018)
- **Variables principales** :
  - Connaissances sur le VIH/sida.
  - Attitudes envers les personnes vivant avec le VIH.
  - Pratiques de dépistage.
  - Facteurs sociodémographiques (âge, sexe, éducation, etc.).

## Méthodologie

1. **Analyse descriptive** :
   - Description des caractéristiques socio-démographiques.
   - Description des niveaux de connaissance, attitude et pratique.
   
2. **Analyse bivariée** :
   - Tests de Chi-deux pour identifier les facteurs associés au dépistage.

3. **Analyse multivariée** :
   - Régression logistique pour modéliser les facteurs indépendamment associés au recours au test VIH.
   - Estimation des Odds Ratios (OR) avec intervalles de confiance à 95%.

4. **Évaluation du modèle** :
   - **Courbe ROC** et calcul de l'**AUC** pour évaluer la discrimination du modèle.

## Technologies utilisées

- **R** version  4.2.2
- Packages :
  - `dplyr`, `ggplot2` pour la manipulation et la visualisation des données
  - `pROC` pour l'analyse ROC
  - `survey` Plan d'echantillonage


## Résultats attendus

- Description claire des niveaux de KAP dans la population.
- Identification des déterminants du recours au dépistage du VIH.
- Développement d'un modèle de prédiction robuste validé par l'AUC.



