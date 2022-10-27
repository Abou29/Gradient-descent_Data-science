# Code de la descente du gradient et application
**I - Coder en python un modèle de régression pour n variables d'entrée (variables explicatives)**

Le code doit pouvoir :

entrainer un modèle : calcul par descente de gradient des coefficients
minimisant la fonction coût ;
afficher le graphe de convergence de la fonction coût ;
réaliser une prédiction : calcul la sortie y à partir d'entrée ;
sortir un score : calcule le coefficient de détermination entre une liste de sorties réelles et une liste de sorties prédites par le modèle. Ajout de termes de régularisation à la fonction coût (Lasso, Ridge, Elastic).

**II - Application du code sur un jeu de données**

Le dataset est composé de 97 observations provenant d'une étude scientifique réalisée en 1989. Les données comprennent 8 prédicteurs et le résultat d'intérêt est lpsa (log de l'antigène spécifique de la prostate).

Les prédicteurs incluent log cavol, log weight, age, lbph, sci , lcp , gleason, pgg45.
