---
title: "Détection de Malwares dans les Systèmes IoT"
date: 2025-04-28
summary: "Système intelligent de détection des malwares pour IoT basé sur l'apprentissage profond (CNN1D) et l'analyse comparative avec des méthodes ML classiques."
tags: ["Cybersécurité", "Deep Learning", "IoT", "Machine Learning"]
categories: ["Projets"]
cover:
  image: "/PFE/CNN1dLoss (1).png"
  relative: true
---

La cybersécurité dans les systèmes Internet des objets (IoT) est aujourd'hui un enjeu critique, notamment en ce qui concerne la détection des logiciels malveillants (malwares). Ce projet vise à modéliser un système de détection intelligent permettant aux administrateurs et utilisateurs d’identifier rapidement toute tentative de violation de la sécurité avant qu’elle ne cause des dommages.

Pour atteindre cet objectif, j'ai étudié les performances des principales méthodes d’apprentissage automatique (ML) appliquées à la détection des malwares dans les réseaux IoT. J'ai ensuite développé une approche basée sur l’apprentissage profond en implémentant un **réseau neuronal convolutif unidimensionnel (CNN1D)** adapté aux caractéristiques spécifiques des flux IoT.

Techniquement :
- **Jeu de données** : exploitation de l’ensemble de données de référence **UNSW-NB15**.
- **Détection** : implémentation d’un **CNN1D** pour la classification des flux réseaux comme malicieux ou légitimes.
- **Comparaison** : évaluation de la solution face à plusieurs algorithmes classiques de machine learning.
- **Évaluation** : utilisation de métriques standard (Précision, Rappel, Score F1) ainsi que des indicateurs spécifiques (Taux de détection, Taux de fausses alarmes).

Les résultats expérimentaux ont montré que l’approche par réseau neuronal convolutif surpasse les modèles traditionnels en termes de précision, avec un taux de détection élevé et un taux de fausses alertes très faible, renforçant ainsi la fiabilité du système de détection proposé.

**Mots-clés** : Cybersécurité, Détection de malwares, IoT, Deep Learning, Machine Learning, UNSW-NB15.
