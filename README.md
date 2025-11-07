# OhMyFood — Site “mobile-first” avec animations CSS

[![CI](https://img.shields.io/badge/CI-none-lightgrey)]() [![Licence](https://img.shields.io/badge/Licence-MIT-blue)]()

> Projet : **Dynamisez une page web avec des animations CSS** — OhMyFood (plateforme de restauration).  
> **Objectif général :** implémenter une intégration mobile-first fidèle aux maquettes, avec animations CSS soignées et transition mobile → desktop.

## 📚 Table des matières
- [Description](#-description)
- [Objectifs pédagogiques](#-objectifs-p%C3%A9dagogiques)
- [Compétences & Preuves](#-comp%C3%A9tences--preuves)
- [Stack & Versions](#-stack--versions)
- [Structure du projet](#-structure-du-projet)
- [Fonctionnalités clés](#-fonctionnalit%C3%A9s-cl%C3%A9s)
- [Installation & Lancement](#-installation--lancement)
- [Available Scripts](#available-scripts)
- [Tests](#-tests)
- [Démo & Captures](#-d%C3%A9mo--captures)
- [Roadmap](#-roadmap)
- [Licence](#-licence)
- [Contact](#-contact)
- [English version](#english-version)

---

## 🚀 Description
Intégration **mobile-first** d’une landing page pour OhMyFood (4 menus initiaux). Focus sur animations CSS (menus, transitions, loaders), qualité du responsive et respect strict de la maquette Figma. Livrable : site statique prêt à héberger. 

> **Résultats clés** : intégration mobile-first • animations CSS reproduites • site prêt pour déploiement (GitHub Pages / Netlify).

## 🎯 Objectifs pédagogiques
- Intégrer une maquette mobile-first et assurer la responsivité.  
- Implémenter animations CSS (soignées et performantes).  
- Structurer HTML sémantique et CSS maintenable (SASS optionnel).  
- Préparer le site pour une mise en ligne.

## 🧠 Compétences & Preuves
| Exigence pédagogique | Compétence recrutée | Mise en œuvre | Preuves |
|---|---|---:|---|
| Intégration maquette | **HTML5 / CSS3** | Desktop & mobile fidelity | `index.html`, `css/style.css`, images/ (livrable)  |
| Animations | **CSS animations / transitions** | Menu animé, loader, hover states | `css/animations.css` (ou `scss`) |
| Responsivité | **Mobile-first** | Breakpoints, fluid layout | Tests manuels mobile/tablet/desktop |
| Déploiement | **Static hosting** | Ready for GitHub Pages / Netlify | URL publique (à fournir) |

## 🧰 Stack & Versions
| Tech | Rôle |
|---|---|
| HTML5 | Markup |
| CSS3 / SASS (optionnel) | Styles & animations |
| Vanilla JS (min) | Interactions (menu, animations déclenchement) |
| Static hosting | GitHub Pages / Netlify |

## 🗂️ Structure du projet
```txt
OhMyFood/
├─ index.html
├─ css/
│  ├─ style.css
│  └─ animations.css
├─ js/            # interactions min
├─ images/
└─ README.md
```

## ✅ Fonctionnalités clés
* [x] Intégration mobile-first (menu, vitrines)  
* [x] Animations CSS pour transitions et loader  
* [x] Effets hover & micro-interactions  
* [x] Déploiement possible sur GitHub Pages / Netlify

## ⚡ Installation & Lancement
```bash
# Cloner
git clone https://github.com/devchon2/OhMyFood.git
cd OhMyFood

# Option A — ouvrir localement
open index.html

# Option B — servir localement
npx http-server -c-1 .   # ou python -m http.server 8080
# Ouvrir http://localhost:8080
```

## 📜 Available Scripts
*(Projet statique — adapter si un package.json est présent)*
```bash
# Installer si package.json présent:
npm install
npm start    # si défini (ex: live-server / http-server wrapper)
```

## 🧪 Tests
* Validation HTML/CSS via W3C.  
* Tests manuels responsive (mobile/tablet/desktop).  
* Vérifier animations sans erreurs console et performance mobile.

## 🎥 Démo & Captures
* Livrable : ZIP contenant `index.html`, `css/`, `js/`, `images/`.  
* Fournir URL publique (Netlify/GitHub Pages) et captures pour la soutenance. 

## 🗺️ Roadmap
* Ajouter tests visuels (Percy) • ajouter CI pour build et déploiement.

## 📝 Licence
MIT (ajouter `LICENSE` si absent).

## 📫 Contact
Rachid Chon — `cgpt1euro@rchon-dev.fr`

---

## English version

<details>
<summary>🇬🇧 Click to expand</summary>

# OhMyFood — Mobile-first site with CSS animations

[![CI](https://img.shields.io/badge/CI-none-lightgrey)]() [![License](https://img.shields.io/badge/License-MIT-blue)]()

> Goal: implement a mobile-first landing page with precise CSS animations following Figma prototypes.

(Full English translation of the French sections: Description, Objectives, Skills & Evidence, Stack, Project structure, Key features, Install & Run, Scripts, Tests, Demo, Roadmap, Licence, Contact.) 

</details>
