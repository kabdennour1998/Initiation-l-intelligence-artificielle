# Initiation-l-intelligence-artificielle
Le jeu de données utilisé dans ce projet porte sur des transactions effectuées par carte de crédit par des titulaires européens au cours du mois de septembre 2013. Les transactions couvrent une période de deux jours et comprennent un total de 284 807 transactions, parmi lesquelles 492 sont frauduleuses.

Ce jeu de données est fortement déséquilibré, la classe positive correspondant aux transactions frauduleuses représentant environ 0,172 % de l’ensemble des observations. Cette caractéristique en fait un cas d’étude représentatif des problèmes réels de détection de fraude bancaire et justifie l’utilisation de techniques spécifiques de gestion du déséquilibre des classes.

Les variables explicatives sont exclusivement numériques et résultent d’une transformation par Analyse en Composantes Principales (PCA). Pour des raisons de confidentialité, les variables originales ne sont pas fournies et aucune information détaillée sur leur signification initiale n’est disponible.

Les caractéristiques du jeu de données peuvent être résumées comme suit :

Les variables V1, V2, …, V28 correspondent aux composantes principales obtenues après application de la PCA.
Les variables Time et Amount n’ont pas été transformées par la PCA.
Time représente le nombre de secondes écoulées entre chaque transaction et la première transaction du jeu de données.
Amount correspond au montant de la transaction.
La variable Class est la variable cible et prend la valeur 1 dans le cas d’une transaction frauduleuse et 0 sinon.
Cette description permet de contextualiser les analyses exploratoires et les traitements appliqués aux données dans les sections suivantes
