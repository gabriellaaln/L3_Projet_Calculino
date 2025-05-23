# L3_Projet_Calculino
Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l'Université Nice Sophia Antipolis


# L3 Calculino_Exemple
Projet Github pour notre présentation finale





# Description du projet

Ce projet de communication sans fil est un projet combinant à la fois Arduino et Github. Celui-ci vise à créer un système électronique interactif tel que ici Calculino, un mélange entre "calcul" et "Arduino". En programmant une carte Arduino et en partageant le code sur GitHub permettant de documenter le projet, de collaborer avec d'autres développeurs et de suivre les modifications, nous avons pu créer un objet électronique en lien avec notre futur métier de professeur des écoles.

En effet, Calculino est un dispositif éducatif interactif que des élèves d’école élémentaire peuvent utiliser en autonomie. Il affiche une série de 20 calculs aléatoires et propose deux réponses possibles. En plus du développement de l'autonomie chez les élèves, celui-ci peut-être adaptable à tous les niveaux, dans différentes matières et rend le calcul mental et posé ludique.


# Materiel utilisé

Lors de la réalisation de notre projet, nous avons utilisé divers outils. L'ensemble du matériel étant le suivant :

1 Carte Arduino UCA
→ C’est le cerveau du projet. Elle génère les calculs aléatoires, récupère les réponses des élèves via les boutons ou le capteur d'inclinaison, pilote l’écran OLED, les LEDs, et gère la communication avec l'ordinateur.

1 Écran OLED 0.96" (I2C)
→ Sert à afficher à l'élève le calcul à résoudre, les deux réponses possibles, ainsi que d'autres informations comme le chrono.

Capteurs d’inclinaison 
→ Détecte si l’élève penche la carte à gauche ou à droite pour choisir entre deux réponses. 

2 boutons poussoirs
→ Proposent une autre méthode de réponse : l’élève peut appuyer sur un bouton pour valider son choix (bouton 1 = réponse 1, bouton 2 = réponse 2).

2 LEDs 
→ Indiquent visuellement à l’élève si sa réponse est correcte (LED verte allumée) ou fausse (LED rouge allumée).

1 Ordinateur
→ Reçoit toutes les réponses via l’application Arduino, et affiche les résultats sous forme de statistiques.
Câblage (1 câble USB-C vers USB-A et plusieurs cordon de raccordement)
→ Alimentent et relis l’ensemble du dispositif.

