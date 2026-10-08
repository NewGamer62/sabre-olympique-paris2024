# 🤺 Sabre Olympique — Paris 2024

[![Site Web](https://img.shields.io/badge/Site%20en%20ligne-JRCANDEV-002654?style=for-the-badge&logo=googlechrome&logoColor=white)](https://projets.jrcan.dev/sabre-olympique/)
[![Projet](https://img.shields.io/badge/SAÉ%20Web-BUT%20Informatique%20S1-CE1126?style=for-the-badge)](https://projets.jrcan.dev/sabre-olympique/)
[![Tech](https://img.shields.io/badge/HTML5%20%2F%20CSS3-Responsive-informational?style=for-the-badge&logo=html5&logoColor=white)](https://projets.jrcan.dev/sabre-olympique/)

Site web statique et responsive dédié à la discipline du **Sabre aux Jeux Olympiques de Paris 2024**, réalisé dans le cadre de la **SAÉ Web (BUT 1 Informatique - Semestre 1)** par l'agence étudiante **WSM (Web Site Maker)**.

🌐 **Accéder au site déployé en ligne :** [https://projets.jrcan.dev/sabre-olympique/](https://projets.jrcan.dev/sabre-olympique/)

---

## 👥 Équipe de Réalisation (WSM — Web Site Maker)

Ce projet a été conçu et développé en équipe :

* **Louis AMEDRO** — *Chef de projet*
* **Valentin MINNEBO** — *Développeur & Concepteur*
* **Jules HERBAUX** — *Développeur & Concepteur*
* **Noa GAILLARD** — *Développeur & Concepteur*

---

## 🎯 Contexte & Objectifs de la SAÉ

Dans le cadre des Jeux Olympiques de Paris 2024, le projet consistait à réaliser un site web vitrine responsive complet pour valoriser une discipline sportive olympique (ici, le **Sabre**) et intégrer une étude documentaire approfondie du marché du sport en France.

### Livrables clés attendus :
- **Site web fonctionnel et responsive** (adapté smartphones, tablettes et ordinateurs de bureau).
- **Hébergement et déploiement** opérationnel sur l'infrastructure **JRCANDEV**.
- **Conception UI/UX documentée** : Wireframes, maquettes desktop/mobile et charte graphique.
- **Étude sectorielle** : Chiffres clés de l'escrime en France, impact COVID, dynamique post-JO et analyse concurrentielle.

---

## 📑 Pages & Contenus du Site

Le site s'articule autour de 4 pages interconnectées :

1. **Accueil (`sources/index.html`)** :
   - Histoire de l'escrime depuis ses origines militaires jusqu'aux premiers Jeux Olympiques modernes de 1896 à Athènes.
   - Présentation comparative des trois armes (épée, fleuret, sabre) : zones de touche, conventions et styles tactiques.
2. **Paris 2024 (`sources/pages/paris-2024.html`)** :
   - Présentation détaillée de la compétition olympique de sabre à Paris.
   - Fiches et trombinoscope des athlètes de l'équipe de France (Sara Balzer, Manon Apithy-Brunet, Boladé Apithy, Sébastien Patrice, Maxime Pianfetti...).
   - Tableau des médailles et présentation du staff/coachs.
3. **Analyse du Marché (`sources/pages/analyse-du-marche.html`)** :
   - Évolution historique du nombre de licenciés FFE (pic à ~66 800 en 2008/2009, rebond à 55 600 licenciés en 2023/2024).
   - Analyse de la résilience post-crise sanitaire (chute de 24 % en 2020/2021).
   - Étude concurrentielle des fabricants et distributeurs d'équipements : *Escrime Diffusion*, *NSL Planète Escrime*, *Prieur Sports*.
4. **Mentions Légales (`sources/pages/mentions-legales.html`)** :
   - Renseignements légaux et hébergement (JRCANDEV).
   - Propriété intellectuelle, politique de confidentialité.
   - Crédits et licences des visuels et icônes utilisés.

---

## 🎨 Charte Graphique & Design System

Le design du site respecte une identité visuelle sportive et moderne (disponible en détail dans [`Charte_graphique.pdf`](Charte_graphique.pdf)) :

### Couleurs
| Couleur | Code HEX | Utilisation |
| :--- | :--- | :--- |
| **Bleu Nuit** | `#002654` | Éléments de structure, contrastes, en-têtes |
| **Rouge Vif** | `#CE1126` | Accents, boutons d'action, rappels olympiques |
| **Noir Profond** | `#000000` | Textes principaux, lisibilité |
| **Blanc Pur** | `#FFFFFF` | Arrière-plans, respiration visuelle |

### Typographies (Google Fonts)
- **Anton** : Titres principaux d'impact (h1, bannières).
- **Cute Font** : Éléments typographiques distinctifs et titres secondaires.
- **Alexandria** : Titres de sections et navigation.
- **Almarai** : Textes de paragraphe et corps de texte pour une lisibilité optimale.

---

## 🗂️ Arborescence du Dépôt

```text
sabre-olympique/
├── Charte_graphique.pdf                  # Spécifications graphiques officielles (couleurs, polices, tailles)
├── consignes.pdf                          # Sujet et exigences pédagogiques de la SAÉ Web
├── README.md                              # Documentation globale du projet
├── maquettes/                             # Maquettes graphiques haute fidélité (PDF)
│   ├── pc/                                # Maquettes pour écrans larges (Desktop)
│   │   ├── pc_maquette_analyse_du_marche.pdf
│   │   ├── pc_maquette_index.pdf
│   │   ├── pc_maquette_mentions_legales.pdf
│   │   └── pc_maquette_paris_2024.pdf
│   └── telephone/                         # Maquettes pour mobiles (Responsive)
│       ├── telephone_maquette_analyse_du_marche.pdf
│       ├── telephone_maquette_index.pdf
│       ├── telephone_maquette_mentions_legales.pdf
│       └── telephone_maquette_paris_2024.pdf
├── wireframes/                            # Schémas de zonage structurel (PDF)
│   ├── pc/
│   │   ├── pc_wireframe_analyse_du_marche.pdf
│   │   ├── pc_wireframe_index.pdf
│   │   ├── pc_wireframe_mentions_legales.pdf
│   │   └── pc_wireframe_paris_2024.pdf
│   └── telephone/
│       ├── telephone_wireframe_analyse_du_marche.pdf
│       ├── telephone_wireframe_index.pdf
│       ├── telephone_wireframe_mentions_legales.pdf
│       └── telephone_wireframe_paris_2024.pdf
└── sources/                               # Code source du site web
    ├── index.html                         # Page principale d'accueil
    ├── css/                               # Feuilles de style CSS
    │   ├── style.css                      # Feuille de style globale et responsive
    │   ├── style-paris-2024.css           # Styles spécifiques Paris 2024
    │   ├── style-analyse-du-marche.css    # Styles spécifiques Analyse de Marché
    │   └── style-mentions-legales.css     # Styles spécifiques Mentions Légales
    ├── pages/                             # Pages secondaires du site
    │   ├── paris-2024.html
    │   ├── analyse-du-marche.html
    │   └── mentions-legales.html
    ├── img/                               # Médias, logos et illustrations optimisés
    └── liens.txt                          # Sources des crédits et icônes
```

---

## 💻 Visualisation Locale

Pour tester et consulter le site en local :

1. **Cloner le dépôt :**
   ```bash
   git clone https://github.com/NewGamer62/sabre-olympique.git
   cd sabre-olympique
   ```

2. **Lancer le site :**
   - Ouvrir directement le fichier `sources/index.html` dans n'importe quel navigateur moderne (Chrome, Firefox, Edge, Safari).
   - Ou avec l'extension **Live Server** de VS Code en ouvrant le dossier `sources/`.

---

## 🔗 Liens Utiles
- 🌐 **Déploiement en production :** [https://projets.jrcan.dev/sabre-olympique/](https://projets.jrcan.dev/sabre-olympique/)
- 📄 **Cahier des charges & consignes :** [`consignes.pdf`](consignes.pdf)
- 🎨 **Charte graphique :** [`Charte_graphique.pdf`](Charte_graphique.pdf)