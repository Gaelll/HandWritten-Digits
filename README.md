# HandWritten Digits

## Contexte

Dans le cadre du cours Python for Data Analysis, il est demandé de faire une analyse d'un dataset.
L'analyse consiste à visualiser, préparer et modéliser les données ainsi qu'une optimisation des performances des modèles.


## Database

Ils ont utilisé des programmes de prétraitement mis à disposition par le NIST pour extraire des bitmaps normalisées de chiffres manuscrits à partir d'un formulaire préimprimé. Sur un total de 43 personnes, 30 ont contribué aux données d'entrainement et les 13 restants aux données de test. Les bitmaps 32x32 sont divisés en non-chevauchement de blocs de 4x4 et le nombre de pixels est comptés dans chaque bloc.
Ceci génère une matrice d’entrée de 8x8 où chaque élément est un entier dans la plage 0..16. Cela réduit la dimensionnalité et donne invariance à de petites distorsions.

Training set : 3823
Test set : 1797
Nombre d'attributs : 64

Tous les attributs en entrée sont des entiers compris entre 0 et 16.
Le dernier attribut est le code de classe 0..9

## Objectifs 

- Prédire le chiffre target grâce aux 64 attributs du dataset,

- Visualisation des données,

- Préparation des données,

- Appliquer différents modèles de machine learning.

- Visualiser les performances de ces différents modèles.