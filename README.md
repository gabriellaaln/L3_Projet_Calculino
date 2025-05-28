# Notre projet Calculino 🏫👩‍🏫
Ce projet est réalisé dans le cadre du module "Communication Sans Fil" en Licence 1 à l'Université Nice côte d'azur. Il est encadré par Fabien Ferrero, Lanteri Jerome et Tombakdjian Lionnel 

Projet réalisé par Allinei Gabriella et Pisano Giulia étudiante en Licence Sciences et Technologies Parcours PPPE (Parcours Préparatoire au Professorat des Écoles) en 3ème année sur le Campus Valrose. 

![image](https://github.com/user-attachments/assets/fc6ba4a5-c78a-49b1-a148-e48369347f2c)

# Description du projet 📝

Ce projet de communication sans fil est un projet combinant à la fois Arduino et Github. Celui-ci vise à créer un système électronique interactif tel que ici Calculino, un mélange entre "calcul" et "Arduino". En programmant une carte Arduino et en partageant le code sur GitHub permettant de documenter le projet, de collaborer avec d'autres développeurs et de suivre les modifications, nous avons pu créer un objet électronique en lien avec notre futur métier de professeur des écoles.

En effet, Calculino est un dispositif éducatif interactif que des élèves d’école élémentaire peuvent utiliser en autonomie. Nous avons choisi de l'utiliser dans le contexte d'une classe de CP (Cycle 2).  Il affiche une série de 6 calculs aléatoires et propose deux réponses possibles. En plus du développement de l'autonomie chez les élèves, celui-ci peut-être adaptable à tous les niveaux, dans différentes matières et rend le calcul mental et posé ludique.

# Materiel utilisé 👩‍💻🔧

Lors de la réalisation de notre projet, nous avons utilisé divers outils. L'ensemble du matériel étant le suivant :

➡️ 1 Carte Arduino UCA

C’est le cerveau du projet. Elle génère les calculs aléatoires, récupère les réponses des élèves via les boutons, pilote l’écran OLED, les LEDs, et gère la communication avec l'ordinateur.

➡️ 1 Écran OLED 0.96" (I2C)

Sert à afficher à l'élève le calcul à résoudre, les deux réponses possibles. Il est possible d'afficher d'autres informations comme un chronomètre. 

➡️ 2 Boutons poussoirs inclus sur la carte UCA

Proposent une autre méthode de réponse : l’élève peut appuyer sur un bouton pour valider son choix (bouton 1 = réponse 1, bouton 2 = réponse 2).

➡️ Bandeau de 20 LEDs inclus sur la carte UCA

Indiquent visuellement à l’élève si sa réponse est correcte (LEDs vertes allumées) ou fausse (LEDs rouges allumées).

➡️ 1 Ordinateur

Reçoit toutes les réponses via l’application Arduino, et peut éventuellement afficher les résultats sous forme de statistiques dans le moniteur série de l'application Arduino.

➡️ Câblage (1 câble USB-C vers USB-A et plusieurs cordon de raccordement)

Alimentent et relis l’ensemble du dispositif.

# Motivation 💪

-> Préparer un outil concret pour notre futur métier de professeur des écoles 

-> Suivre les progrès en temps réel grâce au numérique

-> Expérimenter la mise en place d’un projet pédagogique mêlant numérique et apprentissages fondamentaux des élèves 

-> Mieux comprendre comment différencier les approches selon le niveau des élèves

# Problématique ❓

"Comment concevoir un outil à la fois intuitif et interactif, pour entraîner les élèves efficacement tout en facilitant le suivi de leur progression par l'enseignant ?" 

# Fonctions techniques réalisées 💻✅

✅ Utilisation claire et adaptée aux élèves de CP (Cycle 2).

✅ Phrase d’introduction « La série va commencer », suivie d’un chronomètre de 10 secondes (cela permet à l’élève de se préparer mentalement avant de commencer l’exercice).

![image](https://github.com/user-attachments/assets/0d7e6bb9-43cc-47dd-976e-361d369a755a)
![image](https://github.com/user-attachments/assets/7a842ada-8458-4487-8b91-9275a5e66cd3)

✅ Série de 6 calculs aléatoires chacun avec 2 réponses possibles.

![image](https://github.com/user-attachments/assets/d2bb4df6-bfbe-4e59-87c0-1eb91616a487)

✅ Calculs adaptés au niveau des élèves de CP (additions et soustractions seulement et nombres compris entre 1 et 10).

✅ Sélection de la réponse avec les boutons poussoirs présents sur la carte UCA.

✅ Affichage d’un message en fonction de la réponse “Bravo :) ou Oups :(”.

✅ Retour visuel avec les LEDs (vert pour juste, rouge pour faux).

![image](https://github.com/user-attachments/assets/016dbead-c963-46cd-b040-aff16b8a152e)
![image](https://github.com/user-attachments/assets/daf8477f-39bc-4883-be00-b5ac13a987e4)

✅ Affichage du score à la fin de la série.

![image](https://github.com/user-attachments/assets/ccb6a569-e301-41fd-b8e4-7e7c0e3c5d63)


# Pistes d'amélioration 📈✏️

🤔 L’ajout lors des séances notées d’une contrainte de temps avec un décompte de 10 secondes pour chaque calcul.

-> Permet de tester la rapidité de raisonnement des élèves, tout en ajoutant un léger défi motivant. 

🤔 Système de remontée des résultats vers l’ordinateur de l’enseignante.

-> Consultation automatiquement des statistiques de chaque élève : taux de réussite, temps de réponse, types d’erreurs fréquentes… 

🤔 Système de correction automatique sur la carte elle-même, affichant immédiatement la réponse qui est correcte. 

-> Offre un retour immédiat à l’élève, favorisant l’auto-correction et l’apprentissage en autonomie. 

Ces améliorations techniques rendraient l’outil non seulement plus interactif, mais aussi plus utile d’un point de vue pédagogique. 🤓👆

# Les différentes utilisations 👩‍🏫

Cet outil présente un grand potentiel d’adaptation, ce qui en fait un support pédagogique particulièrement intéressant. Dans notre projet, nous avons choisi de le programmer pour des élèves de CP, avec une série de six calculs simples composés uniquement d’additions et de soustractions, et avec des nombres n'excédant pas 10, ce qui permet de rester dans un cadre adapté à leur niveau.

Mais on pourrait aussi : 

📌 Augmenter le nombre de questions.

📌 Élargir la plage des nombres jusqu’à 1 000.

📌 Introduire d'autres opérations telles que les multiplications et les divisions pour les élèves plus avancés. 

📌 Autre variante : les compléments à 10 (ex : 7 + ? = 10). 

📌 Transposition dans d’autres disciplines : en français, il pourrait proposer des phrases à trous où l’élève doit choisir le mot correctement orthographié parmi plusieurs propositions ; en histoire, il pourrait prendre la forme de questions « vrai » ou « faux » sur les notions vues en classe.

# Notre Planning réaliste ⭐️

![image](https://github.com/user-attachments/assets/d4212f84-b584-4a0d-be0c-a9056a3cca11)

# Conclusion et Perspectives 

**Conclusion :**

-> Concevoir un dispositif pédagogique innovant et accessible nous a permis de réfléchir concrètement à la place des outils numériques dans nos pratiques de classe.

-> Ce projet de CSF a été pour nous une véritable opportunité d’allier la technique à notre futur métier d’enseignantes.

-> Notre engouement pour ce projet reflète notre ambition d’être des enseignantes dynamiques, créatives et ouvertes à l’innovation pédagogique.

**Perspectives :**

✅ Continuer à apprendre et à s’inspirer des nouvelles technologies pour enrichir nos pratiques éducatives.

✅ Intégrer des dispositifs similaires dans nos futures classes pour rendre les apprentissages plus ludiques et interactifs.

