# 🎮 Chroniques d'Aethermoor • Interface RPG

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/fr/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/fr/docs/Web/JavaScript)

Une interface de jeu de rôle (RPG) immersive et interactive avec un design dark fantasy. Ce projet démontre les capacités des technologies web modernes pour créer des interfaces de jeu riches et engageantes.

## 📋 Table des matières

- [Aperçu](#-aperçu)
- [Fonctionnalités](#-fonctionnalités)
- [Technologies utilisées](#-technologies-utilisées)
- [Installation](#-installation)
- [Utilisation](#-utilisation)
- [Raccourcis clavier](#-raccourcis-clavier)
- [Structure du projet](#-structure-du-projet)
- [Personnalisation](#-personnalisation)
- [Compatibilité](#-compatibilité)
- [Crédits](#-crédits)
- [Licence](#-licence)

## 🎯 Aperçu

**Chroniques d'Aethermoor** est une interface RPG complète qui reproduit fidèlement l'expérience d'un véritable jeu de rôle. Elle présente tous les éléments classiques du genre : système de progression, gestion d'inventaire, dialogues interactifs, et bien plus encore.

### Captures d'écran

L'interface comprend :
- 🎭 **Écran de chargement** avec barre de progression et conseils
- 🧙 **HUD personnage** avec barres de vie, mana et endurance
- 📜 **Panneau de quêtes** avec suivi de progression
- 🎒 **Système d'inventaire** avec raretés d'objets
- ⚔️ **Barre de compétences** avec cooldowns
- 💬 **Système de dialogue** avec effet machine à écrire
- 🗺️ **Mini-carte** interactive
- 🎵 **Contrôles audio** (lecture, pause, volume)

## ✨ Fonctionnalités

### Interface Utilisateur
- ✅ **Design Dark Fantasy** : Thème visuel immersif avec animations fluides
- ✅ **Responsive Design** : Adaptation automatique mobile, tablette et desktop
- ✅ **Animations CSS** : Particules flottantes, effets de lumière, transitions douces
- ✅ **Curseur personnalisé** : Curseur thématique pour une immersion totale

### Systèmes de jeu
- ✅ **Gestion du personnage** : Affichage niveau, classe, points de vie/mana/endurance
- ✅ **Système de quêtes** : 
  - Quêtes principales et secondaires
  - Suivi de progression (ex: 3/4 fragments collectés)
  - Récompenses XP et objets
- ✅ **Inventaire** :
  - Catégories (Armes, Armures, Consommables, Quête)
  - Système de rareté (Commun, Rare, Épique, Légendaire, Mythique)
  - Compteurs d'objets empilables
- ✅ **Compétences** :
  - 8 emplacements de compétences
  - Système de cooldown visuel
  - Animations d'activation
- ✅ **Équipement** :
  - 4 emplacements (Arme, Bouclier, Casque, Armure)
  - Indicateurs d'objets équipés
- ✅ **Statistiques** :
  - Attaque, Défense, Puissance Magique
  - Résistance, Vitesse, Précision
  - Gestion de l'or

### Dialogues et interactions
- ✅ **Système de dialogue** :
  - Effet machine à écrire
  - Portraits de personnages
  - Choix multiples avec conséquences
  - Récompenses visibles pour certains choix
- ✅ **Notifications** :
  - Système de notifications toast
  - Animations d'apparition/disparition
  - Icônes et messages contextuels

### Audio
- ✅ **Musique de fond** : Ambiance sonore immersive
- ✅ **Contrôles audio** :
  - Lecture/Pause
  - Contrôle du volume
  - Bouton muet
  - Auto-play au premier clic

### Fonctionnalités pédagogiques
- ✅ **Modal d'information RPG** :
  - Explication complète du genre RPG
  - Définitions et caractéristiques
  - Types de RPG
  - Exemples concrets
  - Historique du genre

### Navigation
- ✅ **Menus** :
  - Menu principal (ESC)
  - Options de sauvegarde
  - Paramètres
- ✅ **Raccourcis clavier** : Navigation rapide et intuitive

## 🛠️ Technologies utilisées

### Frontend
- **HTML5** : Structure sémantique
- **CSS3** : 
  - Variables CSS personnalisées
  - Flexbox et Grid
  - Animations et transitions
  - Media queries
- **JavaScript Vanilla** : 
  - Manipulation du DOM
  - Gestion des événements
  - Animations dynamiques
  - Système audio

### Bibliothèques externes
- **Google Fonts** :
  - Cinzel (titres et interface)
  - Crimson Text (texte de corps)
  - MedievalSharp (titres décoratifs)
- **Bootstrap Icons** : Icônes vectorielles

### Audio
- **Musique de fond** : Via Pixabay (licence libre)

## 📦 Installation

### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Aucune dépendance serveur nécessaire

### Étapes d'installation

1. **Cloner ou télécharger le projet**
```bash
git clone [URL_DU_REPO]
cd chroniques-aethermoor
```

2. **Structure des fichiers**
```
chroniques-aethermoor/
│
├── index.html          # Fichier principal
├── README.md           # Documentation
└── assets/             # (optionnel)
    ├── favicon/
    └── images/
```

3. **Lancer le projet**
   - Ouvrir `index.html` directement dans votre navigateur
   - OU utiliser un serveur local :
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Node.js
   npx http-server
   ```

4. **Accéder à l'interface**
   - Navigateur : `file:///chemin/vers/index.html`
   - Serveur local : `http://localhost:8000`

## 🎮 Utilisation

### Premier lancement
1. L'écran de chargement s'affiche automatiquement
2. La musique démarre au premier clic
3. L'interface RPG s'affiche avec tous les panneaux

### Interactions disponibles

#### Bouton d'information RPG
- Cliquez sur le **bouton "?"** en haut à droite
- Lisez l'explication complète sur les RPG
- Fermez avec X, Échap, ou clic en dehors

#### Dialogues
- Lisez les dialogues qui s'affichent progressivement
- Cliquez sur un choix pour continuer l'histoire
- Appuyez sur **Espace** pour accélérer l'affichage du texte

#### Compétences
- Cliquez sur une compétence pour l'activer
- Observez l'animation de cooldown
- Les barres de stats se mettent à jour

#### Inventaire
- Appuyez sur **I** ou cliquez sur l'icône sac à dos
- Naviguez entre les onglets (Tout, Armes, Armures, etc.)
- Cliquez sur un objet pour l'examiner

#### Menu principal
- Appuyez sur **ESC** pour ouvrir le menu
- Options : Reprendre, Sauvegarder, Charger, Options, Quitter

## ⌨️ Raccourcis clavier

| Touche | Action |
|--------|--------|
| `ESC` | Ouvrir/Fermer le menu principal |
| `I` | Ouvrir/Fermer l'inventaire |
| `J` | Journal de quêtes (notification) |
| `M` | Carte du monde (notification) |
| `K` | Compétences (notification) |
| `1-5` | Utiliser les compétences 1 à 5 |
| `Q` | Utiliser la compétence 6 (épée) |
| `E` | Utiliser la compétence 7 (soin) |
| `R` | Utiliser la compétence 5 (ultime) |
| `Espace` | Accélérer le texte des dialogues |

## 📁 Structure du projet

```
index.html (Principal)
├── <head>
│   ├── Meta tags (SEO, Open Graph, Twitter Card)
│   ├── Google Fonts
│   └── Bootstrap Icons
│
├── <style>
│   ├── Variables CSS (couleurs, polices, transitions)
│   ├── Reset & Base
│   ├── Animations (@keyframes)
│   ├── Composants UI
│   │   ├── HUD personnage
│   │   ├── Panneau de quêtes
│   │   ├── Inventaire
│   │   ├── Dialogues
│   │   ├── Compétences
│   │   └── Notifications
│   ├── Modal RPG Info
│   ├── Contrôles audio
│   └── Responsive (Media queries)
│
└── <body>
    ├── Bouton RPG Info
    ├── Modal RPG Info
    ├── Écran de chargement
    ├── Fond de scène
    ├── Particules
    ├── Conteneur principal
    │   ├── HUD supérieur
    │   ├── Contrôles latéraux
    │   ├── Panneau de quêtes
    │   ├── Scène centrale
    │   ├── Panneau de dialogue
    │   ├── Mini-carte
    │   └── Barre de compétences
    ├── Menu principal (overlay)
    ├── Inventaire (overlay)
    ├── Notifications
    ├── Contrôles audio
    ├── Audio (musique de fond)
    └── <script>
        ├── Gestion écran de chargement
        ├── Génération particules
        ├── Système de dialogues
        ├── Gestion compétences
        ├── Gestion inventaire
        ├── Gestion menus
        ├── Notifications
        ├── Événements clavier
        ├── Régénération stats
        ├── Système audio
        └── Modal RPG Info
```

## 🎨 Personnalisation

### Modifier les couleurs

Éditez les variables CSS dans la section `:root` :

```css
:root {
    --color-gold: #d4a853;        /* Couleur principale */
    --color-purple: #6b4c9a;      /* Accent secondaire */
    --color-bg-dark: #0a0a0f;     /* Fond principal */
    /* ... */
}
```

### Modifier les dialogues

Éditez le tableau `dialogueData` dans le JavaScript :

```javascript
const dialogueData = [
    {
        speaker: "Nom du personnage",
        avatar: "🎭",
        text: "Votre texte ici...",
        choices: [
            { text: "Choix 1", reward: null },
            { text: "Choix 2", reward: "⚔️ +100 XP" }
        ]
    }
];
```

### Ajouter des quêtes

Dupliquez et modifiez un élément `.quest-item` dans le HTML :

```html
<div class="quest-item">
    <div class="quest-header">
        <div class="quest-icon">🏰</div>
        <div class="quest-content">
            <div class="quest-name">Nom de la quête</div>
            <div class="quest-desc">Description...</div>
            <div class="quest-progress">
                <div class="progress-bar">
                    <div class="progress-bar-fill" style="width: 50%;"></div>
                </div>
                <span>5/10</span>
            </div>
            <div class="quest-reward">
                <i class="bi bi-gem"></i>
                1500 XP • Récompense
            </div>
        </div>
    </div>
</div>
```

### Personnaliser l'audio

Remplacez l'URL de la musique dans la balise `<audio>` :

```html
<audio id="bgMusic" loop>
    <source src="VOTRE_URL_AUDIO.mp3" type="audio/mpeg">
</audio>
```

## 🌐 Compatibilité

### Navigateurs supportés
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

### Appareils
- ✅ Desktop (1920x1080 et plus)
- ✅ Laptop (1366x768 et plus)
- ✅ Tablette (768px et plus)
- ✅ Mobile (320px et plus)

### Fonctionnalités requises
- JavaScript activé
- CSS3 (animations, grid, flexbox)
- HTML5 Audio API
- LocalStorage (pour futures fonctionnalités)

## 🎓 Utilisation pédagogique

Ce projet est idéal pour :
- **Apprendre le développement web** : HTML, CSS, JavaScript
- **Comprendre les interfaces de jeu** : UX/UI gaming
- **Étudier les animations CSS** : transitions, keyframes
- **Découvrir le responsive design** : media queries
- **Pratiquer la manipulation du DOM** : événements, création dynamique

### Points d'apprentissage
1. **CSS avancé** : Variables, Grid, Flexbox, Animations
2. **JavaScript** : Événements, Timers, Audio API, LocalStorage
3. **Design patterns** : Séparation HTML/CSS/JS, Composants réutilisables
4. **Accessibilité** : Aria labels, Navigation au clavier
5. **Performance** : Optimisation animations, Chargement lazy

## 📝 Améliorations futures

### Fonctionnalités planifiées
- [ ] Système de sauvegarde (LocalStorage)
- [ ] Plus de dialogues et de quêtes
- [ ] Combats interactifs
- [ ] Système de craft d'objets
- [ ] Arbre de compétences
- [ ] Mini-jeux intégrés
- [ ] Mode multi-langues
- [ ] Thèmes alternatifs
- [ ] Effets sonores
- [ ] Système d'achievements

### Améliorations techniques
- [ ] Optimisation des animations
- [ ] Service Worker (mode hors ligne)
- [ ] Tests unitaires
- [ ] Documentation JSDoc
- [ ] Build system (Webpack/Vite)
- [ ] TypeScript migration

## 👤 Crédits

### Développement
- **Auteur** : MODE 83
- **Type** : Projet éducatif / Démonstration

### Ressources externes
- **Polices** : [Google Fonts](https://fonts.google.com/)
  - Cinzel by Natanael Gama
  - Crimson Text by Sebastian Kosch
  - MedievalSharp by Wojciech Kalinowski
- **Icônes** : [Bootstrap Icons](https://icons.getbootstrap.com/)
- **Musique** : [Pixabay](https://pixabay.com/music/) (Licence libre)

### Inspiration
Ce projet s'inspire des interfaces RPG classiques de jeux tels que :
- The Witcher 3
- Skyrim
- Final Fantasy XIV
- World of Warcraft
- Baldur's Gate 3

## 📄 Licence

Ce projet est mis à disposition à des fins éducatives et de démonstration.

### Utilisation autorisée
- ✅ Utilisation personnelle et éducative
- ✅ Modification et personnalisation
- ✅ Apprentissage et étude du code
- ✅ Utilisation en cours/formation

### Restrictions
- ❌ Utilisation commerciale sans autorisation
- ❌ Redistribution sans attribution
- ❌ Violation des licences des ressources externes

### Attribution
Si vous utilisez ce projet, merci de créditer :
```
Interface RPG "Chroniques d'Aethermoor" par MODE 83
https://github.com/[votre-repo]
```

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Fork le projet
2. Créez une branche (`git checkout -b feature/AmazingFeature`)
3. Committez vos changements (`git commit -m 'Add some AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrez une Pull Request

### Guidelines
- Respectez le style de code existant
- Commentez les fonctions complexes
- Testez sur plusieurs navigateurs
- Mettez à jour la documentation

## 📞 Contact

- **Organisation** : MODE 83
- **Email** : [contact@mode83.fr](mailto:contact@mode83.fr)
- **Site web** : [www.mode83.fr](https://www.mode83.fr)
- **Lieu** : Draguignan, France

## 🙏 Remerciements

Merci à tous ceux qui ont contribué à ce projet et aux créateurs des ressources open source utilisées.

---

<div align="center">

**🎮 Bon voyage dans l'univers d'Aethermoor ! ⚔️✨**

[⬆ Retour en haut](#-chroniques-daethermoor--interface-rpg)

</div>
