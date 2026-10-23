# Le Fort des Défis

Un jeu d'aventure en 3D à jouer en équipe (de 1 à 4 enfants, de 4 à 13 ans), directement dans le navigateur.

On arrive en bateau devant un fort posé sur la mer, puis on marche soi-même sur la passerelle jusque dans la cour intérieure. La cour a deux étages : un escalier monte à la galerie. Au rez-de-chaussée comme à l'étage, chaque porte cache une épreuve, et chaque épreuve réussie donne une clé. L'équipe choisit 7 épreuves parmi les 10 portes : avec 7 clés, la grille du trésor se lève.

## Les épreuves

À chaque nouvelle partie, les portes de la cour reçoivent 9 épreuves tirées au sort parmi 16, et les énigmes sont choisies dans une grande réserve : on ne retombe pas sur les mêmes tant qu'on ne les a pas toutes vues. Le bouton « Nouvelle partie » au départ relance une partie toute neuve.

- **Les cloches** : en haut de la tour, rejouer la mélodie des cloches dans le bon ordre.
- **Les ombres** : retrouver l'ombre qui correspond à l'objet.
- **Les crabes** : sur la plage, attraper les crabes quand ils sortent du sable.

- **Les cartes** : retrouver les paires.
- **Les coquillages** : compter jusqu'à 9.
- **La pêche** : attraper 8 poissons.
- **L'intrus** : trouver celui qui n'est pas de la même famille.
- **Les devinettes** : écouter les devinettes de Papi Goémon, le vieux gardien à la barbe blanche.
- **L'énigme de la vigie** : en haut de la tour de guet, résoudre les énigmes en rimes du Père Trouillard, le gardien froussard, et de son vieux hibou.
- **Le labyrinthe** : rejoindre la clé avant que le sablier soit vide.
- **Les jarres** : suivre des yeux la jarre qui cache la clé.
- **Le pont de corde** : traverser en gardant l'équilibre.
- **La cellule d'eau** : pomper vite pour faire remonter la clé.
- **Le rondin** : avancer sur un tronc qui tourne au-dessus de l'eau sans tomber, en gardant l'équilibre.
- **La corniche** : dehors, tout en haut du fort, avancer sur une corniche au-dessus du vide sans se laisser emporter par le vent.
- **Le plongeon** : sauter du haut du fort dans la mer, nager sous l'eau pour trouver la clé cachée dans un coquillage géant, sans se faire toucher par les poissons-serpents.
- **Le mur d'escalade** : dehors, sur la façade du fort au-dessus de la mer, grimper jusqu'à la clé en évitant les prises qui s'effritent.
- **La grotte au trésor** : attraper un maximum de pièces d'or en 25 secondes.

Deux petits mousses, Pip et Pop, accompagnent l'équipe partout dans le fort. Un perroquet lit toutes les consignes à voix haute, donc pas besoin de savoir lire.

## En équipe et contre la montre

- Au départ, on indique les prénoms et l'âge des joueurs. Ils jouent chacun leur tour, et la difficulté s'adapte à l'âge de celui qui joue (durée du sablier, nombre de cartes, taille du labyrinthe, énigmes plus difficiles pour les grands…).
- Chaque épreuve a un sablier. S'il se vide avant la fin, le joueur est fait prisonnier : il doit résoudre une énigme du Père Trouillard pour être libéré. La porte se referme sans clé, mais on peut retenter l'épreuve plus tard.

## Jouer

Ouvrir la page GitHub Pages du dépôt, ou ouvrir `index.html` dans un navigateur récent (Chrome, Edge, Firefox ou Safari) avec une connexion internet.

- Cliquer sur le sol pour marcher, ou utiliser les flèches du clavier.
- Cliquer sur une porte (ou sur le petit plan en bas à droite) pour y aller et entrer.
- Faire glisser la souris pour regarder autour de soi.
- Le bouton 🌊 coupe le bruit de la mer, et le bouton 💬 répète ce que dit le perroquet.

La progression (les clés gagnées et le prénom du capitaine) est gardée dans le navigateur.

## Technique

Un seul fichier HTML, sans installation. La façade du fort (fenêtres creusées, encadrements, bandeaux, corniche) et la tour de guet (créneaux, mâchicoulis, meurtrières) sont modélisées dans Blender et chargées depuis `assets/fort.glb` et `assets/tour.glb` ; si un fichier manque, le jeu dessine une version simplifiée. La 3D utilise [three.js](https://threejs.org) r128. Les textures de pierre et de bois et le ciel sont des photos libres de droits (CC0) de [Poly Haven](https://polyhaven.com), chargées au lancement ; si elles ne sont pas disponibles, le jeu utilise des textures dessinées par le code. Les sons, la musique et la mer sont générés par le code. Si un fichier `assets/audio/generique.mp3` est présent à côté de `index.html`, il est joué au départ (volume 30 %, bouton 🔊 pour le couper) à la place de la musique générée.

Jeu original créé par Estelle Lavenac.
