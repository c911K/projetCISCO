# Projet Réseau Multi-Étage avec VLAN, NAT, GRE, VoIP et HSRP

[![Status](https://img.shields.io/badge/Status-Completed-brightgreen)]()
[![Technologies](https://img.shields.io/badge/Tech-Cisco%20Packet%20Tracer-blue)]()

Ce projet illustre la conception et la mise en place d’un réseau d’entreprise **multi-étages**, intégrant :

- **Segmentation par VLAN**  
- **Routage inter-VLAN**  
- **VoIP avec téléphones IP**  
- **Connectivité Wi-Fi**  
- **Sécurité réseau**  
- **NAT pour accès Internet simulé**  
- **Tunnel GRE pour site distant**  
- **Haute disponibilité via HSRP**

---

## Objectifs du projet

1. **Segmenter le réseau interne par VLAN**  
   Isoler les différents types d’équipements : PC, serveurs, imprimantes, téléphones IP et Wi-Fi.

2. **Configurer le routage interne et l’accès Internet simulé**  
   Mise en place du NAT pour permettre la connectivité externe.

3. **Déployer un système VoIP**  
   Utilisation de CallManager Express (CME) pour gérer les téléphones IP.

4. **Mettre en place un tunnel GRE**  
   Simuler la connexion d’un site distant.

5. **Assurer la haute disponibilité des passerelles**  
   Implémentation de HSRP pour garantir la continuité du service.

6. **Sécuriser le réseau**  
   - Création d’ACL pour contrôler l’accès entre VLANs  
   - Isolement des VLANs pour Wi-Fi visiteurs et honeypot

---

## Topologie du réseau

La topologie complète du réseau simulé avec **Cisco Packet Tracer** :  

[![Topologie du réseau](topologie.png)](topologie.png)

---

## Technologies et outils utilisés

- **[Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)** – simulation et configuration des équipements réseau  
- **VLAN & Routage inter-VLAN** – segmentation et communication entre réseaux  
- **NAT** – traduction d’adresses pour l’accès Internet simulé  
- **GRE** – tunnel pour site distant  
- **HSRP** – redondance des passerelles  
- **CallManager Express (CME)** – gestion VoIP et téléphones IP  
- **ACLs** – sécurité et contrôle d’accès réseau  



