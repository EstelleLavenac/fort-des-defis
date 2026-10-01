# Le Fort des Défis

Un jeu d'aventure en 3D pour les enfants à partir de 6 ans, jouable directement dans le navigateur.

On arrive en bateau devant un fort posé sur la mer. Chacune des portes, et la tour de guet, cache une épreuve, et chaque épreuve réussie donne une clé. Avec les six clés, la grille du trésor se lève.

## Les épreuves

- **Les cartes** : retrouver les paires.
- **Les coquillages** : compter jusqu'à 9.
- **La pêche** : attraper 8 poissons.
- **L'intrus** : trouver celui qui n'est pas de la même famille.
- **Les devinettes** : écouter les devinettes de Mamie Caret, la tortue gardienne.
- **L'énigme de la vigie** : dans la tour de guet, résoudre les énigmes en rimes de Maître Hulotte, le vieux hibou.
- **La grotte au trésor** : attraper un maximum de pièces d'or en 25 secondes.

Un perroquet lit toutes les consignes à voix haute, donc pas besoin de savoir lire.

## Jouer

Ouvrir la page GitHub Pages du dépôt, ou ouvrir `index.html` dans un navigateur récent (Chrome, Edge, Firefox ou Safari) avec une connexion internet.

- Cliquer sur une porte pour lancer une épreuve.
- Faire glisser la souris pour tourner autour du fort, et utiliser la molette pour zoomer.
- Le bouton 🌊 coupe le bruit de la mer, et le bouton 💬 répète ce que dit le perroquet.

La progression (les clés gagnées et le prénom du capitaine) est gardée dans le navigateur.

## Technique

Un seul fichier HTML, sans installation. La 3D utilise [three.js](https://threejs.org) r128 chargé depuis cdnjs. Les textures, les sons et la mer sont générés par le code.

Jeu original créé par Estelle Lavenac.
