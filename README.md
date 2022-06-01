# OpenClassroom projets libre 
Ce projet faisait partie du parcours data analyst  d'Openclassroom - Classe de 2022

### 1. Source du Dataset : 

- Ensemble de données sur la qualité du vin. Cet ensemble de données est également disponible dans le dépôt d'apprentissage automatique de l'UCI (https://archive.ics.uci.edu/ml/datasets/wine+quality).
- Contexte du jeu de données : Deux jeux de données sont inclus, liés à des échantillons de vin rouge et de vin blanc provenant du nord du Portugal. L'objectif est d'utiliser les échantillons de vin rouge pour modéliser la qualité du vin rouge sur la base de tests physico-chimiques.

- Input variables (baser sur des tests physico-chimiques.):
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Output variable (based on sensory data):
12 - quality (score between 0 and 10)


### 2. Définition du problème et variable cible : 
Ce projet vise à déterminer quelles caractéristiques chimiques sont les meilleurs indicateurs de la qualité du vin rouge. Pour être plus précis, nous définissons les problèmes suivants
pour cette analyse :
- Montrer la contribution de chaque facteur à la qualité du vin dans notre modèle.
- Montrer quelles caractéristiques sont les plus importantes dans la détermination de la qualité du vin.
- Montrer quelles caractéristiques sont moins importantes dans la détermination de la qualité du vin.
Comme mentionné précédemment, notre variable cible sera la qualité du vin, qui est notée entre 0 et 10.

### 3. Scénario d'utilisation : 
L'industrie du vin connaît une récente poussée de croissance en raison de l'augmentation de la consommation sociale. Le prix du vin dépend d'un concept plutôt abstrait d'appréciation du vin par les dégustateurs,
dont l'opinion peut être très variable. Le prix du vin dépend dans une certaine mesure de ce facteur volatile. Les tests physico-chimiques sont un autre facteur essentiel de la certification et de l'évaluation de la qualité du vin. Ils sont effectués en laboratoire et prennent en compte des facteurs tels que l'acidité, le pH, le sucre et d'autres propriétés chimiques. Il serait intéressant pour le marché du vin que la qualité de la dégustation humaine puisse être liée aux propriétés chimiques du vin afin que les processus de certification et d'évaluation et d'assurance de la qualité soient mieux contrôlés.

### 4. Techniques utiliser lors du projets : 
- EDA (Exploratory Data Analysis)
- Regression Modeling
- LASSO
- Random Forest

### 5. liste des different fichier du projets
- Data set: winequality-red.csv
- List of R-codes: P8_codesource.Rmd 
- Report document: P8_Aourik_khalid

### 6. reference :
- https://monvinnature.com/analyse-chimique
- https://www.oenologie.fr/oeno/analyse/analysechim1.shtml/

##### inspiration du rapport :
- https://tel.archives-ouvertes.fr/tel-01281917/file/these_A_ROULLIER_GALL_Chloe_2014.pdf

### 7. autre information :
N/A

si vous avez des issuse à exécuter de code dans Rstudio, vous devez télécharger et importer dans rstudio les version suivante de certains packages :

        - dataQualityR 1.0 https://cran.r-project.org/src/contrib/Archive/dataQualityR/
        - randomForest 4.7-1 https://cran.r-project.org/src/contrib/Archive/randomForest/
        - mice 3.14.0 https://cran.r-project.org/src/contrib/Archive/mice/
