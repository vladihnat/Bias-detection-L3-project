# Bias-detection-L3-project
Bias detection on a Chest X-ray (NIH 14) dataset

# Rapport d'analyse de fairness sur des radiographies thoraciques

## Contenu du notebook

Ce fichier Jupyter Notebook (`projet_PENA-CASTANO_Javier_HERRERA-NATIVI_Vladimir.ipynb`) contient un rapport complet analysant les biais dans un modèle de détection de symptômes radiologiques. Il comprend :

- Le chargement et prétraitement des données
- L'analyse exploratoire des distributions
- Plusieurs méthodes de mitigation de biais (reweighting, DIR, uniform sampling)
- Des techniques de post-processing (reject-option, calibrated equalized odds)
- L'évaluation des résultats via différentes métriques de fairness

## Structure du rapport

Le rapport est rédigé directement dans le notebook, avec des explications au fur et à mesure du code. Les sections principales sont :

1. Contexte et objectifs
2. Méthodologie globale
3. Analyse quantitative des données
4. Pré-processing (3 méthodes)
5. Post-processing (2 méthodes)
6. Résultats et métriques

Les commentaires et analyses sont intégrés dans les cellules Markdown entre les blocs de code, formant un rapport exécutable et interactif.
