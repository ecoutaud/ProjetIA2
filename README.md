# ProjetIA2
Elsa Coutaud, Esther Cros, Mallory Le Corre

## Régréssion du prix des voitures : 

Plusieurs méthodes ont été employé pour évaluer l'impact des différents facteurs dans le prix des voitures. 

Tout d'abord, nous avons fais les différentes régréssions linéaires simples possibles.
Dans cette situation les régréssions obtenus ont parut être pertinente. Les kilométrages, l'année de fabrication et la puissance ont d'après ce test un impact important sur le prix de la voiture.

Afin de vérifier cette hypothèse nous avons choisi de faire une matrice de corrélation des facteurs. L'objectif étant d'observer une forte corrélation entre le prix et les facteurs identifiés précédemment.
L'hypothèse du kilométrage et de la puissance sont validés (plus d'informations sont en commentaire du script "Regression_Projet2_Coutaud_Cros_LeCorre.ipynb") tandis qu'un doute est identifié pour l'année de fabrication.

Enfin, nous avons fais un modèle de machine learning de régréssion linéaire basique pour à nouveau confronter nos résultats. Là encore le kilométrage et la puissance sont notés comme significatifs tazndis que l'année de fabrication semble un peu moins certaine. 

On regarde ainsi afin de confirmer ou d'infirmer ces hypothèses comment se comporte le prix selon d'autres techniques d’analyse de données et de machine learning. 

## Classification : 

Pour cette partie, nous avons utilisé deux méthodes : une méthode de machine learning classique (ClassificationML_Coutaud_Cros_LeCorre.ipynb) et une méthode sur des réseaux de neurones (ClassificationRN_Coutaud_Cros_LeCorre.ipynb).
