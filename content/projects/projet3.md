---
title: "Conception d’un VPN Poste à Site avec pfSense"
date: 2025-04-28
summary: "Mise en place et configuration d’un réseau privé virtuel (VPN) sécurisé basé sur pfSense et OpenVPN pour assurer la confidentialité et l’intégrité des communications."
tags: ["VPN", "Cybersécurité", "pfSense", "OpenVPN", "Sécurité réseau"]
categories: ["Projets"]
cover:
  image: "/crypto/schema.png" # <-- Remplace par ton chemin d'image si besoin
  relative: true
---

Les réseaux privés virtuels (**VPN**) jouent un rôle essentiel dans la sécurisation des communications en permettant l’établissement de connexions chiffrées entre des utilisateurs distants et un réseau internet. Ce projet a pour objectif de concevoir et de configurer un VPN **poste à site** basé sur **pfSense** afin de garantir la confidentialité et l’intégrité des échanges.

Pour atteindre cet objectif, j'ai procédé comme suit :
- **Étude** : analyse des différents types et architectures de VPN ainsi que des protocoles de chiffrement utilisés.
- **Mise en œuvre** : installation de **pfSense** sur **une machine virtuelle**, génération des certificats (**autorité de certification, certificat serveur, certificats clients**), et configuration d’**un tunnel sécurisé**.
- **Configuration** : reconfiguration du modem pour permettre le routage du trafic VPN, installation et configuration du client **OpenVPN**.
- **Validation** : tests de connexion et analyse de la sécurisation effective des flux réseau.

Le système mis en place assure une connexion sécurisée avec un haut niveau de protection contre les menaces extérieures, offrant ainsi une solution robuste pour le travail à distance ou les connexions réseau sensibles.

**Mots-clés** : VPN, pfSense, OpenVPN, Chiffrement, Sécurité réseau, Poste à site, Cybersécurité.
