### **Jour 1 : Introduction et Normalisation des Réseaux**

#### **Objectifs du module :**
- Comprendre les concepts de base des réseaux informatiques.
- Appréhender l’importance de la normalisation dans les réseaux.
- Explorer les modèles de référence OSI, IEEE 802, et IETF.
- Mettre en pratique la compréhension des modèles à travers des exercices.

---

### **Partie 1 : Introduction aux Réseaux Informatiques**

#### **1.1. Définition et Importance des Réseaux Informatiques :**
- **Réseaux informatiques :** Un réseau informatique est un ensemble d’ordinateurs et d’autres dispositifs connectés pour partager des ressources, comme des fichiers, des imprimantes ou une connexion internet.
- **Importance :**
  - **Communication efficace :** Permet la transmission rapide des données entre utilisateurs et systèmes.
  - **Partage de ressources :** Optimise l’utilisation des ressources matérielles et logicielles.
  - **Accessibilité :** Accès à distance aux informations et aux applications.
  - **Collaboration :** Facilite le travail en groupe et la gestion de projets en temps réel.

#### **1.2. Types de Réseaux :**
- **LAN (Local Area Network) :** Réseau local limité à un bâtiment ou un campus.
- **MAN (Metropolitan Area Network) :** Couvrant une ville ou une grande zone urbaine.
- **WAN (Wide Area Network) :** Couvrant des zones géographiques plus vastes, comme des pays ou des continents (ex : Internet).
- **PAN (Personal Area Network) :** Réseau personnel pour les appareils autour d’un individu (ex : Bluetooth).

#### **1.3. Composants des Réseaux :**
- **Équipements :**
  - **Routeurs :** Relient différents réseaux et dirigent le trafic.
  - **Switches :** Connectent des dispositifs au sein d’un même réseau.
  - **Points d’accès :** Permettent la connexion des dispositifs sans fil.
- **Médias de transmission :** Câbles (cuivre, fibre optique) et sans fil (Wi-Fi).

---

### **Partie 2 : Modèles de Normalisation des Réseaux**

#### **2.1. Pourquoi la Normalisation ?**
- **Interopérabilité :** Les normes permettent à différents équipements et logiciels de fonctionner ensemble de manière cohérente.
- **Compatibilité :** Garantit que les dispositifs de différents fabricants peuvent communiquer.
- **Sécurité :** Les normes intègrent des pratiques pour la protection des données.
- **Évolution technologique :** Les standards facilitent l’intégration de nouvelles technologies.

#### **2.2. Modèle OSI (Open Systems Interconnection) :**
- **Introduction :** Le modèle OSI est un cadre conceptuel standardisé qui divise les fonctions réseau en sept couches pour une meilleure compréhension et standardisation.
  
- **Les 7 Couches du Modèle OSI :**
  1. **Couche Physique (Layer 1) :** Transmission brute des données via des câbles, ondes radio, etc.
  2. **Couche Liaison de Données (Layer 2) :** Gestion des connexions physiques, correction d’erreurs (ex : Ethernet).
  3. **Couche Réseau (Layer 3) :** Routage des paquets de données (ex : IP).
  4. **Couche Transport (Layer 4) :** Contrôle de la transmission des données, fiabilité (ex : TCP).
  5. **Couche Session (Layer 5) :** Gestion des sessions de communication.
  6. **Couche Présentation (Layer 6) :** Formatage des données pour l’application (ex : cryptage).
  7. **Couche Application (Layer 7) :** Interface utilisateur (ex : HTTP, FTP).

- **Avantages :**
  - Facilite le dépannage réseau.
  - Aide à la conception modulaire des réseaux.

#### **2.3. Norme IEEE 802 :**
- **Introduction :** L’IEEE (Institute of Electrical and Electronics Engineers) 802 est un ensemble de standards pour les réseaux locaux et métropolitains.
  
- **Principales Normes :**
  - **IEEE 802.3 :** Norme pour Ethernet, le protocole dominant pour les réseaux câblés.
  - **IEEE 802.11 :** Norme pour les réseaux sans fil (Wi-Fi).
  - **IEEE 802.1Q :** Norme pour les VLAN (Virtual Local Area Network).

#### **2.4. IETF (Internet Engineering Task Force) :**
- **Introduction :** L’IETF est un organisme international responsable de la normalisation des protocoles Internet, en particulier ceux qui composent la pile TCP/IP.
  
- **Principales Contributions :**
  - **RFC (Request for Comments) :** Documents publiés par l’IETF définissant les standards Internet.
  - **Protocole TCP/IP :** Base de l’Internet moderne.
  - **Normes de sécurité :** TLS/SSL pour les communications sécurisées.

---

### **Partie 3 : Pratique - Exercices sur les Modèles et la Standardisation des Réseaux**

#### **Exercice 1 : Identifier les Couches du Modèle OSI**
- **Objectif :** Associer des technologies réseau aux couches OSI correspondantes.
- **Activité :** Pour chaque technologie (ex : routeurs, switches, câbles, protocoles), déterminez la couche OSI concernée.

#### **Exercice 2 : Explorer le Protocole Ethernet (IEEE 802.3)**
- **Objectif :** Comprendre les bases du protocole Ethernet.
- **Activité :** Configuration de base d’un réseau Ethernet avec des switches et câblage correct.

#### **Exercice 3 : Découverte des RFC de l’IETF**
- **Objectif :** Rechercher et analyser un RFC pertinent sur les protocoles TCP/IP.
- **Activité :** Utiliser le site de l’IETF pour trouver et résumer un RFC sur un protocole réseau spécifique.

#### **Exercice 4 : Simulation de Réseaux avec des Outils Virtuels**
- **Objectif :** Pratiquer la création de réseaux simulés pour tester les normes étudiées.
- **Activité :** Utiliser un simulateur de réseau (ex : Cisco Packet Tracer, GNS3) pour créer un réseau local basé sur les normes vues.
