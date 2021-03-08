# Station-Météo

Ce projet est une station météo destinées à être embarquée sur des bateaux sur de longues durées pour collecter des données sur l'air ambiant
La sation fonctionne avec une Arduino UNO et est équipée d'un capteur de pression, d'humidité, de température et de luminosité ainsi qu'une horloge pour dater les mesures.
les données collectées sont mises en formes et stockées sur une carte SD.
Les boutons permettent de naviguer entre les différents modes disponibles : mode standard, mode maintenance, mode économie.

Mode standard : 

La LED est allumée en vert. une mesure est effectuée toutes les 10 minutes (paramètre par défaut)

Mode économie : 

La LED est allumée en bleu. même fonctions que le mode standard mais fait une mesure sur deux.

Mode maintenance : 

La LED est allumée en jaune. effectue les mesures et les affiche sur le port série. ce mode est utilisé pour changer la carte SD


Le paramétrage est disponible avec le fichier "config.ino"
