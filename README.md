# Intervalle-de-confiance
### Exercice 1:
On s’intéresse aux rendements journaliers de bourse de l’indice Standard and Poors 500
de 1990 à 1999. On prend 2780 valeurs du fichier "SP500" de la librairie "MASS" comme
population. On note μ et σ² la moyenne théorique et la variance théorique du rendement.
Après une étude statistique préalable (test de la normalité), on suppose raisonnablement
que la population admet une loi normale N(μ,σ²)avec les deux paramètres inconnus
(mais cette approximation n’est pas de bonne qualité, ce qui implique que le coefficient de
confiance n’est pas très précis).
1. Install.packages("MASS"); library(MASS)
2. Sauvegarder ces N = 2780 valeurs du rendement du fichier "SP500" dans une
variable nommée Population.
3. Générer une réalisation (x1...xn) d’un échantillon (X1...Xn) avec n=28 , puis construire
l’intervalle de confiance de μ de niveau de confiance 1 − α = 95%. Contient-il la
valeur de μ = mean(Population) ?
4. Générer 100 réalisations d’un échantillon (X1...Xn) avec n=28 , puis construire 100
réalisations de l’intervalle de confiance de μ de niveau de confiance 1 − α = 95%.
Quel est le pourcentage des réalisations qui ne contiennent pas le paramètre μ =
0.04575267 ?
