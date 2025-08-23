## Projet Réseau Multi-Étage avec VLAN, NAT, GRE, VoIP et HSRP

Ce projet illustre la conception et la mise en place d’un réseau d’entreprise multi-étages, intégrant la segmentation par VLAN, le routage inter-VLAN, la VoIP, la connectivité Wi-Fi, la sécurité réseau, le NAT, un tunnel GRE et la haute disponibilité via HSRP.

Objectifs principaux :

1. Créer un réseau interne segmenté par VLAN pour isoler les différents types d’équipements (PC, serveurs, imprimantes, téléphones IP, Wi-Fi).

2. Configurer un routage interne et un accès Internet simulé via NAT.

3. Déployer un système VoIP avec CallManager Express (CME) pour les téléphones IP.

4. Mettre en place un tunnel GRE simulant un site distant.

5. Assurer la haute disponibilité des passerelles avec HSRP.

6. Sécuriser certains segments réseau avec des ACL et isoler des VLANs pour Wi-Fi visiteurs et honeypot.

La topologie complète du réseau simulé avec Cisco Packet Tracer :

![Topologie du réseau](topologie.png)
