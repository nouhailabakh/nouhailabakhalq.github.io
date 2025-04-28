---
title: "Système Intelligent de Gestion de l’Éclairage Public"
description: "Ajustement automatique de l'intensité lumineuse en fonction de la luminosité ambiante et de la détection de présence grâce à des capteurs PIR et LDR, avec envoi des données vers ThingSpeak."
dateString: Avril 2025
draft: false
tags: ["Arduino", "PIR", "LDR", "IoT", "ThingSpeak"]
showToc: false
weight: 200
cover:
  image: "/IoT/simulation1.png"
---

## Description

Ce projet vise à développer un **système intelligent de gestion de l’éclairage public** capable d’ajuster automatiquement l’intensité lumineuse en fonction de la luminosité ambiante et de la présence humaine ou de véhicules.

Pour atteindre cet objectif, le système utilise :
- Un **capteur PIR** pour détecter les mouvements (présence humaine ou passage de véhicules).
- Un **capteur LDR** pour mesurer la luminosité extérieure.
- Une **carte Arduino simulée** pour contrôler dynamiquement l’allumage et l’extinction des lampes selon les données captées.

Les informations collectées, telles que la fréquence des déclenchements, l'état de l'éclairage et la consommation énergétique, sont envoyées vers la **plateforme IoT ThingSpeak** pour permettre une surveillance et une analyse en temps réel.

Ce système permet ainsi une **gestion optimisée de l’éclairage urbain**, renforçant la **sécurité** tout en diminuant les **coûts énergétiques** et en réduisant l’**impact environnemental**.

### Détails techniques :
- **Capteur PIR** : détection de mouvement.
- **Capteur LDR** : mesure de la luminosité ambiante.
- **Carte Arduino simulée** : contrôle des lampes.
- **Intégration IoT** : envoi des données vers **ThingSpeak** pour visualisation et analyse.

---

**Mots-clés** : Capteur PIR, Capteur LDR, Arduino simulé, Luminosité ambiante, Optimisation énergétique, ThingSpeak.
