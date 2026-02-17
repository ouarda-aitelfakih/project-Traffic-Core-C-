# 🌆 Smart City Traffic Simulation — Ma Contribution

> 🔗 **Projet original :** [Traffic-Core](https://github.com/fatimazahraeelbouhssini4-arch/Traffic-Core)  
> 👥 **Projet réalisé en groupe** dans le cadre de mes études  
> 🍴 Ce dépôt est un fork personnel pour mettre en valeur ma contribution

---

## 👩‍💻 Ma Contribution Personnelle

Dans ce projet de simulation de trafic urbain en **C++ / Raylib**, j'ai été responsable de :

### 🗺️ Architecture Routière & Logique de Navigation
- Conçu la **logique des routes, nœuds et intersections** — la base sur laquelle tous les véhicules se déplacent
- Mis en place le système de **graphe de navigation** permettant aux véhicules de trouver leur chemin dans la ville
- Défini les règles de priorité aux intersections et la topologie du réseau routier

### 🏙️ Environnement 3D
- Intégré l'**environnement 3D** : bâtiments, mobilier urbain et éléments de décor
- Assuré la cohérence visuelle entre les éléments de la ville et le réseau routier

### 🔧 Intégration & Gestion des Conflits
- Géré la **fusion des modules** développés par les différents membres du groupe
- Résolu les **conflits d'intégration** entre les branches Git pour maintenir un projet stable
- Assuré la compatibilité entre les composants (véhicules, routes, rendu graphique)

---

## 📌 Description du Projet

Une simulation de trafic urbain intelligente développée en **C++17** avec **Raylib**. Le projet modélise des véhicules autonomes naviguant dans une ville avec des intersections, des ronds-points et une physique de conduite réaliste.

**Technologies utilisées :** C++17 · Raylib · CMake · Ninja/MinGW

---

## ✨ Fonctionnalités Principales

- Trajectoires fluides via **courbes de Bézier** aux intersections
- Gestion avancée des **ronds-points** avec priorités de circulation
- **Navigation par graphes** (chemin le plus court)
- Rendu 3D avec modèles de véhicules texturés
- Caméra multi-modes (orbital, vol libre, suivi de véhicule)

---

## 🚀 Lancer le Projet

```bash
git clone https://github.com/fatimazahraeelbouhssini4-arch/Traffic-Core.git
cd Traffic-Core
mkdir build && cd build
cmake .. -G "Ninja"
cmake --build .
./SmartCity.exe
```

---

## 🎮 Contrôles Rapides

| Touche | Action |
|--------|--------|
| **V** | Ajouter un véhicule |
| **SPACE** | Pause / Reprise |
| **1 / 2 / 3** | Changer le mode caméra |
| **TAB** | Changer de véhicule suivi |
| **M** | Menu de configuration |

---

## 👥 Équipe du Projet

| Membre | GitHub |
|--------|--------|
| Ouarda Ait El Fakih | [@ouarda-aitelafkih](https://github.com/ouarda-aitelafkih) |
| Fatima Zahra El Bouhssini | [@fatimazahraeelbouhssini4-arch](https://github.com/fatimazahraeelbouhssini4-arch) |
| Halima Achabbak | [@achabbakhalima-ai](https://github.com/achabbakhalima-ai) |
| Fatima Boumehaout | [@Fatimaboumehaout](https://github.com/Fatimaboumehaout) |

---

## 📄 Licence

Distribué sous la licence **MIT**. Voir `LICENSE` pour plus d'informations.

