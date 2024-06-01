Conception et Développement d'un Système Temps Réel et Multi-tâche : Gestion Automatisée de Téléviseurs dans une Maison Intelligente (Via un ESP32 et l'OS FreeRTOS) (Programmation Concurentielle).

Resumé du projet : 
Ce projet consiste à concevoir et développer un système temps réel et multitâche utilisant une carte ESP32 avec le système d'exploitation FreeRTOS. Le but principal est de contrôler automatiquement les télévisions d'une maison intelligente en fonction de la luminosité ambiante et de la détection de mouvement. Les télévisions doivent répondre à des contraintes temporelles et logiques spécifiques, comme ne pas allumer plus de deux télévisions à la fois pendant la journée et s'éteindre automatiquement après deux heures d'utilisation.

Les fonctionnalités principales du système incluent :
Allumer un maximum de deux télévisions simultanément pendant la journée en fonction de la luminosité ambiante.
Éteindre automatiquement les télévisions après un délai maximum de deux heures pour économiser de l'énergie.
Afficher un message d'alerte en cas de détection d'intrusion sur l'écran principal.
Éteindre toutes les télévisions pendant la nuit, sauf en cas d'affichage d'un message d'urgence.
Le système utilise le simulateur en ligne WOKWI pour le développement et la simulation. Les composants principaux incluent un capteur de luminosité (LDR), un capteur de mouvement, et trois écrans LCD connectés via I2C.

Lien vers la Simulation : 
https://wokwi.com/projects/398558043039519745

Membre du groupe : 
Moncef YAKINE
Adam SABIR
Bah SALEM
Reda TAYAA
