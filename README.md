Ce projet est réalisé dans le cadre de la formation de cycle d'ingénieur (deuxième année) de l'Ecole Polytechnique de l'Université Côte d'Azur.
***
# Simulation numérique de la distribution de la température dans une chambre par la méthode des différences finies.

## Présentation
Ce projet a été réalisé avec le langage MATLAB.

### Objectifs :
* Elaborer deux plans représentant deux exemples de chambre avec les positions de la porte, des fenêtres et des chauffages qui représentent les conditions aux limites de Dirichlet et de Neumann.
* Simulation statique de la chaleur : calculer la température ambiante dans nos chambres en faisant varier les cas tests. Utilisation du Laplacien et résolution de l'équation de Poisson -Δu = f.
* Simulation instationnaire de la chaleur : observer l’évolution de la température au sein de la pièce au cours du temps. Utilisation du Laplacien mais au lieu de résoudre l’équation de Poisson -Δu = f (partie 1), on résout l’équation de la chaleur par la méthode d’Euler explicite et par la méthode d’Euler implicite. Utilisation d'une boucle en temps dans deux cas test différents.

Exemple de résultat de la simulation statique de la chaleur : Mauvais placement de chauffage en hiver

![alt text](https://github.com/JulienChoukroun/Simulation-Numerique-Temperature-EDP-MATLAB/blob/main/Images/hiver_avec_mauvais_chauffage.jpg "Simulation statique de la chaleur-hiver mauvais chauffages")

Exemple de résultat de la simulation statique de la chaleur : Bon placement de chauffage en hiver

![alt text](https://github.com/JulienChoukroun/Simulation-Numerique-Temperature-EDP-MATLAB/blob/main/Images/chambre2_bon_hiver.png "Simulation statique de la chaleur-hiver bon chauffages")
