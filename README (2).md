# Machine Learning for Predicting Diabetic Patient Readmissions

## Business Use Case (BUC)

# Contexte :
# Le projet vise à prédire les réadmissions des patients diabétiques après une hospitalisation. 
# L'objectif principal est d'aider les hôpitaux à anticiper ces réadmissions, optimisant ainsi la gestion de leurs ressources.

# Impact métier :
# - Gain de temps : Permet aux hôpitaux de planifier les admissions de patients.
# - Développement des dispositifs médicaux : Possibilité de concevoir des dispositifs connectés pour une gestion plus personnalisée des patients.
# - Réduction & maîtrise des coûts : En anticipant les admissions, les hôpitaux peuvent mieux contrôler leurs dépenses.
# - Fidélisation des patients : Une anticipation des besoins des patients favorise une meilleure relation avec la clientèle et peut contribuer à augmenter le chiffre d'affaires.

## Dataset

# Source : Kaggle (Diabetes Dataset)
# Format : CSV
# Nombre de lignes : 101 566
# Description des données :
# - Les données contiennent diverses caractéristiques sur les patients, incluant leur historique médical.
# - Les colonnes avec trop de valeurs manquantes, comme le poids, ont été supprimées.

## Baseline Model

# Modèle : Régression logistique
# Précision obtenue : 0.8872
# Pré-traitement : Les variables catégorielles ont été encodées en variables binaires, et les données ont été divisées en ensembles d'entraînement et de test.

## Première itération

# Changements :
# Le modèle Random Forest a été ajouté pour améliorer les prédictions.

# Impact sur les métriques :
# - Précision : 0.8874
# - Cross-validation : Moyenne de 0.8887
# - Analyse des performances : Bien que le modèle excelle pour les prédictions de la classe négative, il reste des améliorations à apporter pour la classe positive, avec une AUC de 0.64.
