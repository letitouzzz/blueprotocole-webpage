<div align="center">

# BLUE `PROTOCOL`

**Site vitrine officiel — Jeu d'horreur en équipe**

![Status](https://img.shields.io/badge/status-en_développement-c62828?style=flat-square)
![HTML](https://img.shields.io/badge/HTML5-e34f26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572b6?style=flat-square&logo=css3&logoColor=white)

</div>

---

## 📁 Dossier classifié

`BLUE PROTOCOL` est la page d'accueil du jeu vidéo d'horreur du même nom. Quatre agents de police répondent à une intervention de routine dans une bâtisse coloniale abandonnée. Leurs caméras corporelles seront les seuls témoins de ce qu'ils vont y trouver.

Le site adopte une direction artistique **sombre, tactique et cryptique** : esthétique de terminal Bash, dossiers d'enquête caviardés, et équipement de police en toile de fond, pour immerger le visiteur dans l'ambiance du jeu avant même d'y avoir joué.

---

## ✨ Fonctionnalités actuelles

- **Navbar tactique** — navigation stylée `DOSSIER / INCIDENTS / INVESTIGATION / ARCHIVES`
- **Fond d'ambiance** — image en très faible opacité (`body::before`) pour garder une atmosphère sombre sans nuire à la lisibilité
- **Terminal box** — bloc de présentation façon terminal Linux/macOS (points rouge/jaune/vert, prompt bash, texte façon rapport de police avec passages caviardés)
- **Titre vertical en filigrane** — `BLUE PROTOCOL` en typographie condensée, quasi invisible sur le fond, pour habiller l'espace négatif
- **CTA tactique** — bouton `[ DEPLOY_MISSION / ACHETER ]` avec effet de survol

## 🧭 Fonctionnalités prévues

- [ ] HUD caméra corporelle (bodycam) avec voyant REC, horloge en direct et effet de glitch
- [ ] Section "Dossier d'Enquête" avec photos polaroïd de preuves et profils d'agents disparus
- [ ] Lecteur "Fréquence Radio" (ambiance sonore façon talkie-walkie)

---

## 🛠️ Stack technique

| Élément | Détail |
|---|---|
| Structure | HTML5 |
| Style | CSS3 (Flexbox, pseudo-éléments, dégradés) |
| Typographies | [Fira Code](https://fonts.google.com/specimen/Fira+Code) (terminal) · [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) (titre vertical) |

---

## 🚀 Installation locale

```bash
git clone https://github.com/ton-user/blue-protocol.git
cd blue-protocol
```

Ouvre simplement `index.html` dans ton navigateur, ou lance un petit serveur local :

```bash
# Avec Python
python3 -m http.server 8000

# Avec Node (npx)
npx serve
```

### Ajouter les assets locaux

Place tes images dans un dossier `images/` à la racine du projet, puis adapte les chemins dans le CSS :

```css
background-image: url('images/background-police.jpg');
```

---

## 📂 Structure du projet

```
blue-protocol/
├── index.html
├── css/
│   └── style.css
├── images/
│   └── background-police.jpg
└── README.md
```

---

## 📄 Licence

Projet personnel — tous droits réservés, sauf mention contraire.

<div align="center">

*Restez groupés. Économisez vos batteries. Survivez.*

</div>