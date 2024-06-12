---
layout: default
grand_parent: Char
parent: Électronique
nav_order: 1
title: Carte ESP32
---
## ESP32

Pour ce Projet nous avons utiliser un ESP32 WROOM qui est utilisé en WIFI pour se connecter a la télécommande qui est l'application BLYNK
Il est aussi relié à nos deux servos moteurs sur les Borches D2 et D4.



## Dimensionnement Batterie 

1. ESP32-WROOM-32 DevKit
Tension de fonctionnement : 3.3 V
Consommation moyenne : 200 mA 

2. Servo moteur MG996R
Tension de fonctionnement : 4.8 V à 6 V 
Courant en charge maximale : 2.5 A

3. Servo moteur Parallax Inc. rotation continue high speed
Tension de fonctionnement : 4.8 V à 6 V 
Courant en charge maximale : 900 mA

Calcul de la consommation totale :

ESP32-WROOM-32 DevKit : 200 mA
MG996R : 2.5 A
Servo Parallax : 900 mA

Courant total : 200 + 2500 + 900 = 3600 mA

Exemple pour une durée de 1 heure d'utilisation :
Courant total : 3.6 A (ou 3600 mA)

Durée d'utilisation : 1 heure

Capacité de la batterie nécessaire : 
3.6×1=3.6 Ah ou 3600 mAh
Et on peut estimer une tension nécessaire à 5V

On prendra donc une batterie de 5000mAh et 5V de tension,
pour alimenter le char à voile pour une durée d'environ 1h30.
