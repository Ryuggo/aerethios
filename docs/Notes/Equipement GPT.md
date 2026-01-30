## Armes

| Arme     |   1 main   |  2 mains   |
| -------- | :--------: | :--------: |
| Courte   |    1d4     |     -      |
| 1 Main   | 1d6<br>1d4 |     -      |
| 2 Mains  |     -      | 2d4<br>1d6 |
| Hast     |     -      | 2d4<br>1d6 |
| Arc      |     -      |    1d8     |
| Arbalète |     -      |     8      |
| Fusil    |     -      |     40     |
#### Munitions
>Avec arme à distance

D'autres matériaux peuvent être utilisés comme munitions mais n'offrent que des propriétés de VS.

| Matériaux  | Arme             |               Propriétés                |
| ---------- | ---------------- | :-------------------------------------: |
| Tissu      | Arcs & Arbalètes |     -1d4 HP/turn x3 or until heal.      |
| Obsidienne | Arcs & Arbalètes |                 10 dmg                  |
| Plomb      | Fusils & Canons  |          -2 HP/turn until heal          |
| Crystaux   | Tout             | - 1d4 crystaux<br>-1d6 HP/crystal perdu |

## Matériaux
>La propriété VS double le dé de dégâts lorsque l'attaque touche le bon type de cible.

### Principaux

| Matériau   |    Dégâts    |          Propriétés           |
| ---------- | :----------: | :---------------------------: |
| Os         | rareté (1-5) | Enchantements élémentaires x2 |
| Fonte      |      0       |        VS Nécrophages         |
| Fer        |      1       |           VS Bêtes            |
| Bronze     |      2       |        VS Insectoides         |
| Acier      |      3       |          VS Mutants           |
| Titane     |      4       |        VS Invocations         |
| Mythril    |      5       |        VS Elementaires        |
| Palladium  |      6       |           VS Anges            |
| Adamantite |      7       |         VS Draconides         |
| Orichalque |      8       |           VS Démons           |

### Revêtements
>Le revêtement retire les propriétés du matériau principal et applique le sien à la place.

| Matériau  |  Propriétés   |
| --------- | :-----------: |
| Cuivre    |  VS Plantes   |
| Argent    |  VS Hybrides  |
| Sombronce |  VS Naturels  |
| Electrum  |  VS Magiques  |
| Or        | VS Mythiques  |
| Platine   | Vs Humanoides |

## Armures
>AC = Mobilité d'esquive naturelle
>DR = Réduction des dégâts

### Equipement
>AC = Base + Pièces d'armures + Modificateurs (+ Bouclier)
>Lorsqu'une armure se fait toucher par sa faiblesse, seul 50% de sa DR est pris en compte.

L'armure se constitue de plusieurs pièces, chacune permettant d'avoir plus de DR, mais réduisant l'AC.

| Pièce         | AC  | DR (basée sur les matériaux) |
| ------------- | :-: | :--------------------------: |
| Base          | 12  |              -               |
| Cape/ Foulard |  0  |              -               |
| Casque        | -1  |             20%              |
| Bras d'armure | -1  |             10%              |
| Plastron      | -2  |             40%              |
| Jambières     | -2  |             30%              |

>Exemple : un joueur avec un casque en orichalque (50 DR) aura 11 AC et 10 DR.

Le modificateur utilisé pour l'AC dépend du type de matériaux de chaque pièce.
On ne peut utiliser qu'un seul type de modificateur (le modificateur le plus élevé est pris par défaut).

|                Tissu                |  Cuir, Peaux, Ecailles, Os  |
| :---------------------------------: | :-------------------------: |
| Mental<br>(+ Sagesse/ Intelligence) | Dextérité<br>(+ Accrobatie) |

Selon le nombre de pièces utilisant le même matériaux, le modificateur maximum change et d'autres bonus s'appliquent (sur la DR totale actuelle).

| Nombre de pièces |  1  |  2  |    3    |    4    |
| :--------------- | :-: | :-: | :-----: | :-----: |
| **Modificateur** | +1  | +2  |   +3    |   +5    |
| **Bonus**        |  -  |  -  | +10% DR | +25% DR |

### Boucliers

| Armure           | AC  | DR (basée sur les matériaux) |
| ---------------- | :-: | :--------------------------: |
| *Buckler*        | -1  |             25%              |
| Bouclier         | -2  |             50%              |
| Bouclier d'Estoc | -3  |             75%              |
| Pavois           | -4  |             100%             |

### Matériaux
>Détermine la DR, ce qui permet de réduire les dégâts reçus.

>La rareté varie entre 1 et 5 (Déchet, Commun, Peu commun, Rare, Légendaire)

| Matériau       |     DR     |       Faiblesse        |
| -------------- | :--------: | :--------------------: |
| Tissu          |     2      | Tranchant<br>Perforant |
| Peau           | 2 * rareté |       Tranchant        |
| Cuir (bouilli) | 3 * rareté |       Tranchant        |
| Écaille        | 4 * rareté |       Perforant        |
| Os             | 5 * rareté |       Perforant        |
| Métal          |  15 - 40   |       Contondant       |

#### Métaux

| Matériau   | DR  |
| ---------- | :-: |
| Fonte      | 15  |
| Fer        | 18  |
| Bronze     | 21  |
| Acier      | 24  |
| Titane     | 27  |
| Mythril    | 30  |
| Palladium  | 35  |
| Adamantite | 35  |
| Orichalque | 40  |

## Combat

### Jet pour toucher

| Type d'attaque |                   Jet à faire                    |         Score à atteindre          |
| -------------- | :----------------------------------------------: | :--------------------------------: |
| **Mêlée**      |        1d20 + Force/ Dextérité + Maîtrise        |                 AC                 |
| **Distance**   |           1d20 + Dextérité + Maîtrise            |                 AC                 |
| **Magique**    | 1d20 + Mental (Intelligence/ Sagesse) + Maîtrise | AC + Nombre de crystaux à utiliser |

### Jet.s de dégâts
>Résultat - Défense (DR) = Dégâts au HP.

| Mêlée                               | Distance                              | Magie                                          |
| ----------------------------------- | ------------------------------------- | ---------------------------------------------- |
| Dégâts d'arme                       | Dégâts d'arme                         | Dégâts de magie                                |
| Matériaux (& Enchantements)         | Munition (& Matériaux)                | Toile céleste                                  |
| Style<br>*(multiplicateur final )*  | Précision<br>*(multiplicateur final)* | Nombre de crystaux<br>*(multiplicateur final)* |

#### Précision
>Seulement pour les armes à distance.

Si le jet est supérieur au double de l'AC, le joueur double ses dés de dégâts.

## Joueurs
>Ils ont 50 HP

Arek :
AC 6 (-2 bouclier)
DR 20 (+25 bouclier)
"1 main" 2d6 (x2 vs démons) + 18
"1 main" 2d8 (x2 vs Mythiques) + 34

Dara :
AC 6 + 8
DR 9
1 main 1d4 + 13
Courte 1d4 (x2 vs Mythiques) + 23

Haelrak :
AC 6 + 5
DR 9
Hast 2d4 (x2 vs Mythiques) + 17
Fusil 15 + munition

Hazdaim :
AC 6 + 5
DR 9
1 main 1d8 + 8
Arbalète 4 (x2 vs Mythiques) + 23 + munition

Zveindel :
AC 6 + 4
DR 12
magie = 14 crystaux (dé = 1d8 +2) -> Nombre de crystaux * Dé = dmg