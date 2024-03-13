## Clone

```$ git clone https://github.com/thimyxuan/car-rental-delay-analysis.git```

## Dépendances

```$ pip install library_name```

Pour utiliser ce projet vous aurez besoin d'installer les librairies ci-dessous.

## Stack technique

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn

## Sujet

Getaround souhaite réduire le nombre d'annulations et de clients insatisfaits à cause des retards dans la remise des véhicules, en particulier dans le cas de locations disposant d'un délai serré (locations consécutives avec un écart de temps court). 

Pour ce faire, l'entreprise souhaite mettre en place un délai minimal au-dessus duquel les voitures n'apparaissent pas dans les résultats de recherche. Nous avons pour mission de trouver le délai optimal. Nous devons également déterminer si cette fonctionnalité devrait être appliquée à tous les véhicules ou seulement ceux équipés de la technologies de check-in Connect.

Dans cette étude nous analysons les locations de voitures en parallèle avec les délais de retour et les annulations. Nous créons un tableau de bord qui résume les informations trouvées. Par ailleurs nous créons une API pour estimer le prix de location journalier d'une voiture.

## Problématique

Le but : 

- Utiliser l'EDA pour :
    - trouver le délai optimal entre deux locations ; 
    - comprendre la part de revenus des locations avec un délai serré ;
    - déterminer sur quelles voitures appliquer le délai minimal.
- Présenter les informations dans un tableau de bord mis en production.
- Créer une API pour rendre la prédiction de prix disponible en ligne.

## Plan 

PARTIE 1 - Analyse exploratoire des données
- Notebook partie_1.ipynb

PARTIE 2 - Machine learning
- Notebook partie_2.ipynb

PARTIE 3 - Tableau de bord Streamlit
- Voir le dossier [getaround_streamlit](https://github.com/thimyxuan/certification-bloc-5/tree/master/getaround_streamlit)

PARTIE 4 - Création de l'API FastAPI
- Voir le dossier [getaround_fastapi](https://github.com/thimyxuan/certification-bloc-5/tree/master/getaround_fastapi)