# Projet N°2 : Concevez une application au service de la santé publique

## Mise en situation :
- **Entreprise :** Santé publique France
- **Logo :**
- **Jeu de données :** [Site officiel](https://world.openfoodfacts.org/) ou [Téléchargement direct](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Donn%C3%A9es+%C3%A9ducatives/Projet+Python_Dataset_Edstats_csv.zip)
- **Description des variables :** [Site officiel](https://world.openfoodfacts.org/data/data-fields.txt)
    - **Les informations générales sur la fiche du produit :** nom, date de modification, etc.
    - **Un ensemble de tags :** catégorie du produit, localisation, origine, etc.
    - Les **ingrédients** composant les produits et leurs **additifs** éventuels.
    - **Des informations nutritionnelles :** quantité en grammes d’un nutriment pour 100 grammes du produit. 
- **Mission :** Trouver une idée innovante d’application en lien avec l'alimentation.

## Réalisations :
- **Librairies principales :** Pandas, Numpy, Seaborn, Matplotlib, tqdm, Random, missingno, scipy, MinMaxScaler...
- **Etapes réalisées :**
    - Ouverture des données.
    - Analyse des données (NaNs (Missingno) et autres informations générales).
    - Choix des variables et des lignes en fonction de l'objectif et du remplissage (Pays, type de nutriment ou d'additifs)
    - **Idées d'application** : Ajouter au nutriscore un environnementscore pour un produit sain et bon pour l'environnement
    - Divers graphiques :
      ![Logo1]()
      ![Logo]()
    - Différents tests de prédiction du Nutrition Grade via les modèles de ML : **KNN**, **Kmeans**, **Decision Tree** et **Régression Logistic**
    - Etude de mon Environnement Grade en **KMeans**
    - Analyse des différents groupes réalisés par le KMeans : **Radar Chart** et analyse statistique par **Tuckey**.




    



