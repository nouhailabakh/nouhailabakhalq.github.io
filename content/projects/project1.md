---
title: "Surveillance de Culture de Betteraves"
description: "Surveiller intelligemment l'état des cultures grâce à un système distribué basé sur Spring Boot, Kafka, TCP Sockets et JAX-WS."
dateString: Avril 2025
draft: false
tags: ["Spring Boot", "Kafka", "React.js", "IoT"]
showToc: false
weight: 200
cover:
  image: "/surveillance-betteraves/arch.png"
---

## Description

La gestion et la surveillance des capteurs et actionneurs dans l'agriculture intelligente représentent des enjeux majeurs pour optimiser la production agricole. Ce projet vise à modéliser un système permettant aux agriculteurs de surveiller en temps réel l’état de leurs équipements répartis sur une large zone et d'analyser les données collectées pour prendre des décisions éclairées.

Pour atteindre cet objectif, j'ai conçu un système distribué basé sur plusieurs services communicants via des technologies comme **JAX-WS** et les **Sockets TCP**. Un tableau de bord interactif permet aux utilisateurs d'observer les mesures en temps réel, de configurer des alertes personnalisées et d'optimiser la gestion des cultures et du bétail.

### Détails techniques :
- **Service TCP** : mesure des températures.
- **Service JAX-WS** : évaluation du pH du sol.
- **Service Spring Boot** : suivi de l'humidité.
- **Backend** : intégration avec Kafka et Firebase pour la collecte et l'analyse des données.

J'ai également mis en place un système d'alertes intelligentes signalant les conditions critiques, offrant ainsi aux agriculteurs des recommandations d'actions correctives. Les données sont visualisées à travers des graphiques interactifs et des rapports détaillés, facilitant la prise de décisions rapides et optimisées.

---

**Mots-clés** : Kafka, JAX-WS, Spring Boot, Sockets TCP, IoT Agricole.
