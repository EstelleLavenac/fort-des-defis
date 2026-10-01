# Le Fort des Défis

Un jeu d'aventure en 3D à jouer en équipe (de 1 à 4 enfants, de 4 à 13 ans), directement dans le navigateur.

On arrive en bateau devant un fort posé sur la mer, puis on marche soi-même sur la passerelle jusque dans la cour intérieure. Tout autour de la cour, chaque porte cache une épreuve, et chaque épreuve réussie donne une clé. Avec les dix clés, la grille du trésor se lève.

## Les épreuves

À chaque nouvelle partie, les portes de la cour reçoivent 9 épreuves tirées au sort parmi 12, et les énigmes sont choisies dans une grande réserve : on ne retombe pas sur les mêmes tant qu'on ne les a pas toutes vues. Le bouton « Nouvelle partie » au départ relance une partie toute neuve.

- **Les cloches** : rejouer la mélodie des cloches dans le bon ordre.
- **Les ombres** : retrouver l'ombre qui correspond à l'objet.
- **Les crabes** : attraper les crabes quand ils sortent du sable.

- **Les cartes** : retrouver les paires.
- **Les coquillages** : compter jusqu'à 9.
- **La pêche** : attraper 8 poissons.
- **L'intrus** : trouver celui qui n'est pas de la même famille.
- **Les devinettes** : écouter les devinettes de Mamie Caret, la tortue gardienne.
- **L'énigme de la vigie** : dans la tour de guet, résoudre les énigmes en rimes de Maître Hulotte, le vieux hibou.
- **Le labyrinthe** : rejoindre la clé avant que le sablier soit vide.
- **Les jarres** : suivre des yeux la jarre qui cache la clé.
- **Le pont de corde** : traverser en gardant l'équilibre.
- **La cellule d'eau** : pomper vite pour faire remonter la clé.
- **La grotte au trésor** : attraper un maximum de pièces d'or en 25 secondes.

Un perroquet lit toutes les consignes à voix haute, donc pas besoin de savoir lire.

## En équipe et contre la montre

- Au départ, on indique les prénoms et l'âge des joueurs. Ils jouent chacun leur tour, et la difficulté s'adapte à l'âge de celui qui joue (durée du sablier, nombre de cartes, taille du labyrinthe, énigmes plus difficiles pour les grands…).
- Chaque épreuve a un sablier. S'il se vide avant la fin, le joueur est fait prisonnier : il doit résoudre une énigme de Maître Hulotte pour être libéré. La porte se referme sans clé, mais on peut retenter l'épreuve plus tard.

## Jouer

Ouvrir la page GitHub Pages du dépôt, ou ouvrir `index.html` dans un navigateur récent (Chrome, Edge, Firefox ou Safari) avec une connexion internet.

- Cliquer sur le sol pour marcher, ou utiliser les flèches du clavier.
- Cliquer sur une porte (ou sur le petit plan en bas à droite) pour y aller et entrer.
- Faire glisser la souris pour regarder autour de soi.
- Le bouton 🌊 coupe le bruit de la mer, et le bouton 💬 répète ce que dit le perroquet.

La progression (les clés gagnées et le prénom du capitaine) est gardée dans le navigateur.

## Technique

Un seul fichier HTML, sans installation. La 3D utilise [three.js](https://threejs.org) r128. Les textures de pierre et de bois et le ciel sont des photos libres de droits (CC0) de [Poly Haven](https://polyhaven.com), chargées au lancement ; si elles ne sont pas disponibles, le jeu utilise des textures dessinées par le code. Les sons, la musique et la mer sont générés par le code.

Jeu original créé par Estelle Lavenac.
