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
| Courir                              | Mouvement x2<br>Impossible d'attaquer                                                                                                                                                      |
| Se désengager                       | Éviter une attaque d'opportunité en s'éloignant d'un adversaire<br>Impossible d'attaquer                                                                                                   |
| Pousser                             | Jet de Force (Athlétisme) pour éloigner la cible de 10ft (2 cases) de soi                                                                                                                  |
| Esquiver                            | Désavantage pour ceux qui attaquent<br>S'annule si le mouvement tombe à 0                                                                                                                  |
| Prendre 10/20<br>(Se concentrer * ) | Prendre son temps (sans se faire perturber) pour réussir les DC de 10 (1 tour) / 20 (2 tours)<br>Permet également de régénérer sa magie                                                    |
| Aider                               | Avantage pour celui qu'on aide (ne se cumule pas)                                                                                                                                          |
| Se cacher                           | Jet de Dextérité (Discrétion) pour se cacher et bénéficier d'un effet de surprise<br>Si ça rate, il faut s'éloigner d'au moins 25ft (5 cases) avant de recommencer                         |
| Se préparer                         | Citer ce que l'on attend qu'il se passe afin de pouvoir y réagir en dehors de son tour                                                                                                     |
| Chercher                            | Jet de Perception (Perception) pour trouver quelque chose                                                                                                                                  |

### Attaquer

#### Jet pour toucher
>Est-ce que l'attaque passe l'armure et la dextérité de la cible.

| Type d'attaque |                   Jet à faire                    |         Score à atteindre          |
| -------------- | :----------------------------------------------: | :--------------------------------: |
| **Mêlée**      |        1d20 + Force/ Dextérité + Maîtrise        |                 AC                 |
| **Distance**   |           1d20 + Dextérité + Maîtrise            |                 AC                 |
| **Magique**    | 1d20 + Mental (Intelligence/ Sagesse) + Maîtrise | AC + Nombre de crystaux à utiliser |

#### Jet.s de dégâts
>Résultat - Défense = Dégâts au HP.

| Mêlée                               | Distance                                        | Magie                                          |
| ----------------------------------- | ----------------------------------------------- | ---------------------------------------------- |
| Dégâts d'arme                       | Dégâts d'arme                                   | Dégâts de magie                                |
| Matériaux (& Enchantements)         | Munition                                        | Toile céleste                                  |
| Style<br>*(multiplicateur final ?)* | Distance/ Précision<br>*(multiplicateur final)* | Nombre de crystaux<br>*(multiplicateur final)* |
| (2d6 T + 2 + (6 + 4 + 6 Feu)) x ?   | (1d8 P + 2 + 10 T) x 3                          | (1d4 + 2 + 1) x 7 crystaux                     |

##### Précision
>Si le jet est supérieur au double de l'AC, le joueur multiplie ses dégâts.

On peut ensuite soustraire 2AC du résultat du jet, et ajouter 1 pour déterminer le multiplicateur de dégâts (seulement ceux qui passent outre l'armure).

>Exemple : Jet(32) - 2 AC(15) + 1 = 3(Multiplicateur de dégâts)

## Actions Bonus
>Peuvent être utilisées en plus d'une action normale

| Action            | Effet                                                                                                          |
| ----------------- | -------------------------------------------------------------------------------------------------------------- |
| Magie de soutient | Utiliser des sorts magiques qui ne nécessitent pas de faire un jet pour toucher (soins, buffs, mouvements, ..) |
| Utiliser un objet | Dans le titre                                                                                                  |