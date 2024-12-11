## **Qu'est-ce qu'un VLAN**
Un VLAN (Virtual Local Area Network) est un réseau local virtuel qui permet de regrouper plusieurs appareils issus de différents réseaux locaux physiques (LAN) en un sous-réseau logique indépendant.<br> Ce concept permet d’améliorer la sécurité, la gestion et l’optimisation du trafic dans un réseau.

> Exemple
> Imagine un switch comme un grand immeuble avec plusieurs appartements. Chaque appartement créé correspond à un VLAN. Si notre immeuble contient 4 appartements,<br> cela correspond à 4 VLANs sur notre switch. Les occupants d’un appartement (c’est-à-dire les appareils du même VLAN) sont indépendants de leurs voisins (appareils de VLANs différents).

## **Fonctionnement** 
Le fonctionnement des VLANs repose sur l’étiquetage des trames Ethernet.<br>
Chaque trame est marquée avec une étiquette spécifique qui indique à quel VLAN elle appartient.<br>
Les commutateurs réseau utilisent ces étiquettes pour acheminer les trames uniquement vers les ports appropriés, garantissant que seuls les appareils du même VLAN puissent communiquer entre eux.


## **Avantages**
Les VLANs offrent plusieurs avantages, notamment :

- Amélioration de la sécurité : en isolant les groupes d’appareils au sein du réseau
- Gestion plus efficace du trafic : en permettant de configurer et de gérer les VLANs séparément
- Optimisation de la bande passante : en répartissant le trafic entre les VLANs
---
## **En résumé**
Un VLAN est un sous-réseau logique qui regroupe des appareils issus de différents LAN physiques, améliorant la sécurité, la gestion et l’optimisation du trafic dans un réseau.
