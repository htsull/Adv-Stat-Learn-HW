# Adv-Stat-Learn-HW

L'idée de ce devoir est la suivante. La plupart des variables descriptives dans ce fichier sont qualitatives.

1. Prédire la survie des passagers en fonction des autres variables qualitatives descriptives de ces passagers. Pour cela, vous disposer du fichier "train" pour apprendre la règle de classification, puis du fichier "test" pour évaluer sa performance de prédiction.

2. Réaliser une réduction de dimension non-supervisée (de type ACM) à partir des données qualitatives en concaténant les deux fichiers fournis (train et test).

3. Réaliser une CCA à partir des deux fichiers concaténés en utilisant d'une part comme table X la variable PtClass qui présente 3 modalités (et qui représente le Pont d'embarquement sur le navire), et comme table Y toutes les autres variables qualitatives. L'idée est de trouver de nouveaux axes de représentation qui sont le plus en lien avec le pont d'embarquement (indicateur de classe sociale des passagers).
