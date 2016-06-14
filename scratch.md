# Scrach

Scratch est un outil développé par le MIT, de type "Visual Coding".
![Scratch screen](http://news.mit.edu/sites/mit.edu.newsoffice/files/images/2013/20130514110054-1_0_0.jpg)

Pourquoi Scratch ?

Scratch permet de s'approprier les logiques de base de la programmation (variables, boucles, conditions, fonctions etc.) sans avoir besoin d'apprendre un langage de programmation.

# Ressources

[Documentation]: <https://scratch.mit.edu/help/>

# TP 1: Dialogue

Choisir 2 lutins, et les faire dialoguer.

Aide:
<p style="color:white;">! Apparence + Contrôle</p>

# TP 2: Dialogue amélioré

Améliorer le dialogue, 2 phrases par lutin (A - B - A - B)

Aide:
>! Apparence + Evenements (Messages)

# TP 3: Château hanté

Scénario:

3 humains discutent dans un château. Au bout d'un moment, un monstre fait son apparition, entraînant une réaction des humains. Le monstre se déplace ensuite, jusqu'à sortir de l'écran.
Appeurés, les humains quittent la scène à leur tour.

Aide:
>! Apparence + Evenements (Messages) + Mouvement (glisser). Il est possible de réagir 2 fois à un même évenement.

# TP 4: Merlin Pinpin

Scénario:

1 magicien lance un sort à un crapaud. Ce sort à 5 issues possibles, aléatoirement:
transformer le crapaud en un autre animal (4 chances sur 5), ou en princesse (1 chance sur 5).
Si le crapaud n'est pas transformé en princesse, il se moque du magicien ("Raté !"), sinon il le remercie ("Merci !")

Aide:
>! Opérateurs (aléatoire) + Apparence + Costumes. Un costume n'a pas qu'un nom.

# TP 5: Fruit ninja

Scénario:

Nous allons créer un jeu de type Fruit Ninja:

![Scratch screen](https://upload.wikimedia.org/wikipedia/en/0/03/FruitNinja_screenshot.png)

Pour simplifier le jeu, nous allons le simplifier:

- Les fruits se déplaceront de haut en bas
- Les fruits disparaissent lorsque l'on clique dessus
- Si on clique sur un fruit, on marque des points
- Si on clique sur une bombe, on perd des points


Réaliser les étapes suivantes:

- Faire apparaître un fruit à un emplacement **aléatoire** en haut de l'écran (y = -180)
- Faire descendre ce fruit à un emplacement **aléatoire** en bas de l'écran
- Rendre la vitesse de déplacement de ce fruit **aléatoire**
- Rendre ce mouvement infini
- Ajouter un temps d'attente **aléatoire** avant la descente du fruit
- Lorsque l'on clique sur le fruit, on marque des points
- Ajouter une bombe, et lui affecter les mêmes mouvements que les fruits
- Lorsque l'on clique sur une bombe, on perd des points
- Ajouter les autres lutins: 5 fruits au total, 3 bombes au total

Astuce: Dupliquer un lutin duplique aussi les scripts que lui sont associés

**Attention**

Si on a 0 points, on ne doit pas en perdre plus si on clique sur une bombe (pas de scores négatifs)

**Bonus**

- Le jeu se termine si on clique sur 3 bombes
- Le jeu se termine après 30 secondes
- Si le jeu se termine à cause des 3 bombes, changer de fond d'écran et afficher un message spécifique
- Si le jeu se termine après 30 secondes, changer de fond d'écran et afficher le score du joueur ("Vous avez marqué 30 points !")
- Afficher 3 icones 'vie' rouges sur l'écran, devenant gris pour chaque vie perdue
- Créer et utiliser des fontions pour simplifier le code

Aide:
>! Opérateurs + Contrôle + Apparence + Costumes + Données + Evenements.

Aide 2:

>! Scratch ne sait pas soustraire. 10 + -1 = ?
