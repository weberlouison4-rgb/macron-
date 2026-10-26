# Macron Coucou 👋

Animation 3D web d'une caricature d'Emmanuel Macron sur une estrade, derrière un pupitre présidentiel, qui fait **coucou de la main comme un maneki-neko** 🐱.

Réalisée avec [Three.js](https://threejs.org/) — aucun asset externe, tout est généré par code.

## 🚀 Lancer l'animation

### Méthode simple (recommandée)

1. Télécharge le fichier [`macron-coucou.html`](./macron-coucou.html)
2. **Double-clique dessus** → il s'ouvre dans ton navigateur et l'animation démarre

Rien à installer : le moteur 3D est intégré dans le fichier.

### Méthode développeur

```bash
git clone https://github.com/weberlouison4-rgb/macron-.git
cd macron-
npm install
npm run dev
# puis ouvrir http://localhost:4321
```

## 🎮 Interactions

| Action | Effet |
|---|---|
| Glisser avec la souris | Orbiter autour de l'estrade |
| Molette | Zoomer / dézoomer |
| Bouton « Vitesse du coucou » | Normal / rapide / paresseux |
| Bouton « Rotation auto » | Caméra en rotation automatique |

## ✨ Ce que contient la scène

- Caricature de Macron : grosse tête, mèche balayée, sourcils fins, grand sourire
- Costume navy avec revers, cravate bleue, rosette tricolore
- Estrade circulaire avec tapis rouge et liseré doré
- Pupitre « RÉPUBLIQUE FRANÇAISE » avec micro
- Deux drapeaux français qui ondulent
- Bandeau flottant « COUCOU ! »
- Confettis tricolores qui tombent en continu
- Animation maneki-neko : bras qui oscille, tête qui hoche, yeux qui clignent, corps qui rebondit

## 📁 Fichiers

- `macron-coucou.html` — version autonome (double-clic)
- `index.html` — version modulaire (nécessite `npm install`)
- `package.json` — dépendances pour la version modulaire
