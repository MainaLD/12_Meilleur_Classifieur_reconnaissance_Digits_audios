# Meilleur_Classifieur_reconnaissance_Digits_audios
Développer un modèle IA pour la reconnaissance des Digits provenant d'un enregistrement audio

## Contexte du projet
Cet atelier a pour objectif de manipuler les différentes techniques de classification supervisée sous Python, comme KNN, SVM, Foret Aléatoire, XGBoos et autre.
Dans cet atelier, nous appliquons apprentissage supervisé pour reconnaitre les Digits à partir d’un enregistrement audio.


**Challenges**
-	Collection d’une base de données.
-	Analyse, prétraitement et visualisation des données.
-	Préparation des données pour l’apprentissage.
-	Préparation de Pipeline en utilisant « sklearn.pipeline.Pipeline ».
-	Choix de meilleur modèle.
-	Vérification de l’efficacité de ce modèle à des nouvelles données.
-	Intégration de ce modèle dans une application pour test temps réel.



## Documents dans ce GitHub :
### 1 notebook Digits_Recognition_Meilleur_modele.ipynb :
pour définir le meilleur modèle de classifieur à l'aide du gridsearch et de pipeline, qui reprend:
- l'exécution du test de base "test.py"
- l'excécution de la fusion des différents fichiers *.csv
- la partie 1 : Base de données, Analyse, Prétraitement et Préparation
- la artie 2 : Développement et entraînement d’un modèle KNN:
    - KNN From Scratch
    - KNN Sklearn
- la partie 3 : mise en place la solution dans l’application de test de personnalité

### 1 notebook Digits_Recognition_Resultat_temps_reel.ipynb :
pour exécuter la prédiction avec le meilleur modèle défini dans le précédant notebook.

### le rapport *.pdf :
qui documente et explique les différentes étapes du notebook

### le dossier tools : 
contenant les fichiers pythons et le meilleur model, dont :
- **tools.py** de base pour l'enregistrement
- **model_pred** qui contient le meilleur modèle de cassifieur
- **tool_pred.py** fichier modifié pour l'intégration du meilleur classifieur

### dossier DataSet :
contenant le fichier *.csv des enregistrment audio

### dossier Rec :
contenant les fichiers audio du dernier jeu d'enregistrement
