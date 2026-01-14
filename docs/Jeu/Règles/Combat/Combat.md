---
tags:
  - Règles
---
>Basé sur les règles de [DnD 5e](https://www.dndbeyond.com/sources/dnd/basic-rules-2014/combat) et [ScS 2.0](https://pdfhost.io/v/AF0iy0MPy_Simultaneous_Combat_System_20_Web.pdf)
>Personnalisé pour nos jdr.

## Hit Points (HP)

- Les HP ne sont pas représentatifs de la vie d'une entité.
	→ S'ils tombent à 0, l'entité doit ramper pour se déplacer et ne peut plus effectuer d'actions (sauf se cacher, rechercher et utiliser un objet).

- Les humanoïdes possèdent tous un **maximum de 50 HP** qui se régénèrent avec du repos (pour peu que la personne ait mangé récemment) ou de la magie.

## Mouvement

La majorité des entités possèdent 6 cases (30ft) de déplacement.

| Mouvement                 | Effet                |
| ------------------------- | -------------------- |
| Marche                    | Mouvement de base    |
| Terrain difficile         | Mouvement / 2        |
| Ramper                    | Mouvement / 2        |
| Se relever                | 50% mouvement        |
| Sauter (avec 10ft d'élan) | Distance = Force     |
| Sauter (sans élan)        | Distance = Force / 2 |

Le mouvement peut être "interrompu" par une action avant de rependre, et ce à plusieurs reprises si besoin.

On ne peut traverser une créature hostile que si elle est 2 fois plus grande/ petite que soi.

On peut passer un passage étroit que s'il n'est qu'une fois plus petit que soi.

## Actions
>Les actions personnalisées sont dotées d'un * .

| Action                              | Effet                                                                                                                                                                                      |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Motiver *                           | Seulement au premier tour, seulement un joueur.<br>Motiver son équipe pour lui donner un avantage/ Faire peur aux adversaires pour leur donner un désavantage (effet et durée selon le MJ) |
| Attaquer *                          |                                                                                                                                                                                            |
| Courir                              | Mouvement * 2<br>Impossible d'attaquer                                                                                                                                                     |
| Se désengager                       | Éviter une attaque d'opportunité en s'éloignant d'un adversaire<br>Impossible d'attaquer                                                                                                   |
| Esquiver                            | Désavantage pour ceux qui attaquent<br>S'annule si le mouvement tombe à 0                                                                                                                  |
| Prendre 10/20<br>(Se concentrer * ) | Prendre son temps (sans se faire perturber) pour réussir les DC de 10 (1 tour) / 20 (2 tours)<br>Permet également de régénérer sa magie                                                    |
| Aider                               | Avantage pour celui qu'on aide (ne se cumule pas)                                                                                                                                          |
| Se cacher                           | Jet de Dextérité (Discrétion) pour se cacher et bénéficier d'un effet de surprise                                                                                                          |
| Se préparer                         | Citer ce que l'on attend qu'il se passe afin de pouvoir y réagir en dehors de son tour                                                                                                     |
| Chercher                            | Jet de Perception (Perception) pour trouver quelque chose                                                                                                                                  |
| Utiliser un objet                   | La même                                                                                                                                                                                    |

### Attaquer

#### Jet pour toucher
>Est-ce que l'attaque passe l'armure et la dextérité de la cible.

| Type d'attaque |                   Jet à faire                    | Score à atteindre |
| -------------- | :----------------------------------------------: | :---------------: |
| **Melée**      |        1d20 + Force/ Dextérité + Maîtrise        |  AC + Précision   |
| **Distance**   |           1d20 + Dextérité + Maîtrise            |  AC + Précision   |
| **Magique**    | 1d20 + Mental (Intelligence/ Sagesse) + Maîtrise |  AC + Précision   |

##### Précision
>Exemple pour une entité de taille normale.

| Distance (m) | Torse | Bras/ Jambes | Tête |
| :----------: | :---: | :----------: | :--: |
|      2       |  + 0  |     + 0      | + 1  |
|    3 - 5     |  + 0  |     + 1      | + 2  |
|    6 - 10    |  + 1  |     + 2      | + 3  |
|   10 - 15    |  + 2  |     + 4      | + 6  |
|   16 - 20    |  + 3  |     + 6      | + 9  |
|   20 - 30    |  + 4  |     + 8      | + 12 |
|     30+      |  + 5  |     + 10     | + 15 |

Le modificateur de précision varie selon la taille de l'entité (ne peut pas descendre la précision en dessous de 0) :

| Minuscule | Petit | Normal | Grand | Enorme | Titanesque |
| :-------: | :---: | :----: | :---: | :----: | :--------: |
|    + 4    |  + 2  |   0    |  - 1  |  - 3   |    - 5     |

#### Jet.s de dégâts
>Dé d'arme + Modificateur + Matériaux + Enchantements + Style

- Le score doit être supérieur à l’armure ennemie pour infliger des dégâts.

- Les styles de combat offrent un bonus si réussis, mais retirent ce bonus en cas d’échec.

- La **réussite du style** dépend de son type.

| Élément   | Description                |
| --------- | -------------------------- |
| Dé d’arme | Varie selon arme           |
| Maîtrises | Arme + Type                |
| Style     | Bonus/Malus selon réussite |
| Matériau  | Bonus selon la qualité     |