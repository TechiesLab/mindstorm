# Bref aperçu des programmes opérationnels
Les programmes présents dans ce répertoire sont testés et opérationnels. Si vous souhaitez collaborer, merci de prévenir l'auteur afin d'éviter les conflits de code.

## Classement alphabétique par nom de fichier
_Pour tous les programmes, attention au port !_

1. _Robert_, [Avance\_clair\_arret_noir.ev3](https://github.com/TechiesLab/mindstorm/blob/master/programmes/operationnels/Avance_clair_arret_noir.ev3)&nbsp;: le robot avance sur fond clair et s'arrête sur fond noir ou très sombre&nbsp;; on peut aisément inverser le comportement, c.-à-d. avancer sur fond noir et s'arrêter sur fond clair.

2. _Robert_, [Detection\_couleurs\_et\_vide.ev3](https://github.com/TechiesLab/mindstorm/blob/master/programmes/operationnels/Detection_couleurs_et_vide.ev3)&nbsp;: Utilisation du capteur de couleur poue détecter une surface ou le vide.
    - Couleurs&nbsp;: capteur de couleur, mesure de la couleur. Avance à 50 sur le blanc, à 20 sur le marron (plancher clair), s'arrête sur le noir.
    - Vide&nbsp;: capteur de couleur, intensité réfléchie. Avance à 20, s'arrête quand le capteur de couleurs rencontre le vide. __/!\ Ne fonctionne que vers l'avant, et on aurait intérêt à bien avancer physiquement le capteur. /!\\__

1. _Robert_, [Evite\_obstacle.ev3](https://github.com/TechiesLab/mindstorm/blob/master/programmes/operationnels/Evite_obstacle.ev3)&nbsp;: capteur IR de proximité. Le robot avance à 50. Si il rencontre un obstacle (IR prox. < 15), il recule de 30 pendant 1 rotation, aléatoirement de 45° à gauche ou 45° à droite. Le programme peut aussi s'arrêter par pousser / relâcher sur le capteur tactile.

2. _Robert_, [Pilotage\_boutons.ev3](https://github.com/TechiesLab/mindstorm/blob/master/programmes/operationnels/Pilotage_boutons.ev3)&nbsp;: Pilotage par boutons, brique ou télécommande.
    - Brique&nbsp;: Déplacements évidents. On peut modifier les paramètres de déplacement, si on le souhaite.
    - Télécommande&nbsp;: Avance avec les 2 boutons de devant; tout droit = les 2, à gauche = bouton droit, à droite = bouton gauche. Recule, le même avec les 2 boutons arrières. On peut modifier si on veut. __/!\ Canal 1, moteurs sur les ports B et C. /!\\__

1. _Robert_, [Suivre\_ligne\_noire.ev3](https://github.com/TechiesLab/mindstorm/blob/master/programmes/operationnels/Suivre_ligne_noire.ev3)&nbsp;: le robot suit une ligne noire à vitesse réduite (10). La ligne noire est placée à droite du capteur. Le programme peut aussi s'arrêter par pousser / relâcher sur le capteur tactile.

