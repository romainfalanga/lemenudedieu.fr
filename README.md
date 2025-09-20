# Le Menu de Dieu 🌌

Une application web interactive explorant les concepts de physique théorique et de relativité.

## 🚀 Fonctionnalités

- **L'univers est une application** : Analogie entre les couches de l'univers et une application informatique
- **Relativité Restreinte** : Calculateur interactif de dilatation temporelle
- **Horizon des Événements** : Visualisation des trajectoires espace-temps dans un trou noir

## 🛠️ Technologies

- React 18 + TypeScript
- Vite
- Tailwind CSS
- Recharts pour les visualisations
- Lucide React pour les icônes

## 📦 Installation

```bash
npm install
```

## 🔧 Développement

```bash
npm run dev
```

## 🏗️ Build

```bash
npm run build
```

## 🌐 Déploiement sur Netlify

1. **Cloner et installer** :
   ```bash
   git clone https://github.com/votre-username/le-menu-de-dieu.git
   cd le-menu-de-dieu
   npm install
   ```

2. **Build le projet** :
   ```bash
   npm run build
   ```

3. **Connecter à GitHub** :
   - Créer un nouveau repository sur GitHub
   - Pousser le code vers GitHub
   ```bash
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/votre-username/le-menu-de-dieu.git
   git push -u origin main
   ```

4. **Déployer sur Netlify** :
   - Connecter le repository GitHub à Netlify
   - Configurer le build command : `npm run build`
   - Configurer le publish directory : `dist`
   - Le fichier `netlify.toml` est déjà configuré

5. **Domaine personnalisé** :
   - Configurer `lemenudedieu.netlify.app` ou votre domaine personnalisé

## 🚀 Déploiement Automatique

Une fois connecté à Netlify, chaque push sur la branche `main` déclenchera automatiquement un nouveau déploiement.

## 📁 Structure du Projet

```
src/
├── components/          # Composants réutilisables
├── pages/              # Pages de l'application
├── utils/              # Utilitaires (calculs physiques)
├── types.ts            # Types TypeScript
└── App.tsx             # Composant principal

dist/                   # Build de production (généré)
├── assets/             # Assets optimisés
├── index.html          # Point d'entrée
└── _redirects          # Configuration Netlify
```

## 🎯 Pages

- `/` - L'univers est une application
- `/relativity` - Calculateur de relativité restreinte  
- `/black-hole-concept` - Horizon des événements

## 🔬 Concepts Physiques

### Relativité Restreinte
- Calcul du facteur de Lorentz (γ)
- Dilatation temporelle
- Relation vitesse/temps

### Trous Noirs
- Horizon des événements
- Inversion espace-temps
- Trajectoires dans l'espace-temps courbé

## 📱 Responsive Design

L'application est entièrement responsive et optimisée pour :
- 📱 Mobile (320px+)
- 📟 Tablette (768px+)
- 💻 Desktop (1024px+)
- 🖥️ Large screens (1440px+)

## 🎨 Design System

- **Couleurs** : Gradients cosmiques (bleu, cyan, violet, rose)
- **Typographie** : Inter + Computer Modern pour les formules
- **Animations** : Particules, effets de lueur, transitions fluides
- **Thème** : Futuriste avec effets holographiques

## 🧮 Calculs Physiques

Les calculs sont basés sur les équations d'Einstein :
- `γ = 1 / √(1 - (v/c)²)`
- `v = c × √(1 - 1/γ²)`

## 🌟 Effets Visuels

- Particules binaires animées
- Effets de lueur et de scan
- Gradients animés
- Grilles futuristes
- Transitions fluides

## 📄 Licence

MIT License - Voir le fichier LICENSE pour plus de détails.

---

Créé avec ❤️ et beaucoup de ☕ pour explorer les mystères de l'univers ! 🌌✨