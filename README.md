# Valentin_Antonin_Mblock_Oskour

Pour ouvrir le fichier, utiliser l'IDE mBlock : https://mblock.cc/pages/downloads.

## 2 mode (manuel et auto) (changer le mode en appuyant sur Espace)

### Mode Manuel

Le robot peut-être dirigée en utilisant les flèches directionnelles pour déplacer le robot. En utilisant la touche B du clavier, la vitesse du moteur change entre 3 valeurs (altèrne entre 50, 100 et 250% de vitesse).

### Mode Auto

Le robot avance automatiquement vers l'avant tout en traçant dans l'espace de visualisation de l'IDE son parcours. Le tracé se base sur la distance théoriquement parcouru via la vitesse, ainsi que sur les rotations mesurées par le gyroscope de l'appareil. Au-delà de 30cm de distance d'un obstacle (mesurée par le module à ultrasons), le robot avant à 50% de puissance. En-dessous de 30 cm, le robot va ralentir linéairement jusqu'à atteindre 0% à 10cm de distance, tout en tournant progressivement à gauche pour éviter l'obstacle devant lui.

## Autres fonctionnalités explorées

### Lumières

Les lumières du robot sont utilisées pour :
- Indiquer si le robot est en mode automatique.
- En mode manuel, indiquer laquelle des trois vitesses est sélectionnée.

### Émetteur sonore

Non exploité dans le programme fourni, un de nos tests à permis de réaliser un radar en combinant le capteur à ultrasons et l'émetteur sonore : plus la distance d'un obstacle est faible, et plus la fréquence sonore émise par le robot était élevée. 
