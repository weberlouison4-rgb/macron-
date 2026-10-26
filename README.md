# Macron Coucou 👋 — Édition Délire

Animation 3D web d'Emmanuel Macron en train de faire **coucou de la main façon maneki-neko** 🐱 derrière son pupitre présidentiel, devant un **public en délire** qui saute, brandit drapeaux et téléphones, sous une pluie de **confettis** avec des **flashs de caméras**.

Réalisé avec [Three.js](https://threejs.org/) — 100 % généré par code, aucun asset externe.

## 🚀 Lancer l'animation

### Méthode simple (recommandée)

1. Téléchargez [`macron-coucou.html`](./macron-coucou.html)
2. **Double-cliquez dessus** → l'animation démarre dans votre navigateur

Rien à installer : le moteur 3D est intégré dans le fichier.

### Méthode développeur

```bash
git clone https://github.com/weberlouison4-rgb/macron-.git
cd macron-
npm install
npm run dev   # puis ouvrir http://localhost:4321
```

## 🎮 Interactions

| Action | Effet |
|---|---|
| Glisser à la souris | Orbiter librement autour de la scène |
| Molette | Zoomer / dézoomer |
| Bouton « Coucou » | Vitesse : normal / rapide / paresseux |
| Bouton « Rotation auto » | Caméra en rotation automatique |
| Bouton « Caméra » | Vues prédéfinies : face / public / plongée / côté |

## ✨ La scène

- **Macron détaillé** : mèche balayée, sourcils, yeux avec paupières qui clignent, sourire avec dents, rosette tricolore, pochette, revers et boutons dorés du costume
- **Public de ~140 personnes** : teints de peau variés, couleurs de cheveux et vêtements aléatoires, chacun saute à son propre rythme en agitant les bras
- **Certains brandissent** des drapeaux français ou filment avec leur téléphone (écran allumé)
- **1600 confettis** tricolores qui tombent en continu
- **Flashs de caméras** aléatoires dans la foule
- **Drapeaux géants** dont le tissu ondule (déformation de maillage en temps réel)
- **Projecteurs** avec cônes de lumière volumétrique
- Estrade avec tapis rouge, pupitre « RÉPUBLIQUE FRANÇAISE » avec discours et micro, banderole « COUCOU ! »

## 📁 Fichiers

- `macron-coucou.html` — version autonome (double-clic, aucune installation)
- `index.html` — version modulaire (nécessite `npm install`)
- `package.json` — dépendances
