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

### Jets pour toucher

|Type d'attaque|Jet à effectuer|Score à atteindre|
|---|---|---|
|**Mêlée**|1d20 + modificateur|AC de la cible|
|**Distance**|1d20 + modificateur|AC de la cible|
|**Magique**|1d20 + modificateur|AC de la cible + Nombre de crystaux dépensés|

#### Précision (armes à distance)

Si le jet dépasse le double de l’AC de la cible, le joueur double les dés de dégâts.

## Joueurs
> Tous les joueurs ont 50 HP au début.

| Joueur   | Modificateur toucher | AC                 | DR                     | Faiblesse | Arme                | Magie  | Crystaux |
| -------- | -------------------- | ------------------ | ---------------------- | --------- | ------------------- | ------ | -------- |
| Arek     | 11                   | 6<br>(-2 bouclier) | 25+5<br>(+25 bouclier) | C         | 2d8 + 34 C          | 1d8 +5 | 9        |
| Dara     | 11                   | 14                 | 11+5                   | T         | 1d4 + 23 P / T      | 1d12   | 9        |
| Haelrak  | 8                    | 13                 | 11+3                   | T         | 2d4 + 17 P          | 1d8    | 14       |
| Hazdaim  | 10                   | 13                 | 11+3                   | T         | 4 + 23 T (distance) | 1d6    | 9        |
| Zveindel | 11                   | 13                 | 15+4                   | T         | -                   | 1d8 +2 | 14       |
| Léoric   | 7                    | 6                  | 18+3                   | C         | 1d6 + 23 C          | 1d8    | 9        |
## Simulation
IMPORTANT : Suis les instructions à la lettre. Ne fais aucune explication, aucun commentaire, aucune justification, aucun calcul intermédiaire. Respecte strictement le format fourni pour chaque attaque. Utilise uniquement les règles et données ci-dessous. Choisis les équipes et cibles aléatoirement si nécessaire, et effectue la simulation tour par tour jusqu’à ce que je dise d’arrêter. Affiche uniquement les lignes dans le format demandé.

FORMAT À RESPECTER :
Joueur vs cible:
Touche : [résultat touche] > AC
Dégâts : [résultat dégâts] - DR = dmg
Cible HP : [nouveaux HP]

RÈGLES :
- Attaques physiques : 1d20 + modificateur > AC de la cible
- Attaques magiques : 1d20 + modificateur > AC + cristaux dépensés
- Chaque attaque magique dépense un nombre choisi de cristaux. Si le joueur n’a plus assez de cristaux, il ne peut pas attaquer magiquement.
- DR de la cible : réduire de 50% si attaque correspond à sa faiblesse
- Dégâts distance doublés si jet > 2 × AC cible
- HP initial : 50 pour tous les joueurs

JOUEURS :

| Joueur   | Modificateur toucher | AC                  | DR                     | Faiblesse | Arme                | Magie  | Crystaux |
| -------- | -------------------- | ------------------- | ---------------------- | --------- | ------------------- | ------ | -------- |
| Arek     | 11                   | 6 <br>(-2 bouclier) | 25+5<br>(+25 bouclier) | C         | 2d8 + 34 C          | 1d8 +5 | 9        |
| Dara     | 11                   | 14                  | 11+5                   | T         | 1d4 + 23 P / T      | 1d12   | 9        |
| Haelrak  | 8                    | 13                  | 11+3                   | T         | 2d4 + 17 P          | 1d8    | 14       |
| Hazdaim  | 10                   | 13                  | 11+3                   | T         | 4 + 23 T (distance) | 1d6    | 9        |
| Zveindel | 11                   | 13                  | 15+4                   | T         | -                   | 1d8 +2 | 14       |
| Léoric   | 7                    | 6                   | 18+3                   | C         | 1d6 + 23 C          | 1d8    | 9        |

INSTRUCTIONS :
1. Forme deux équipes de 3 joueurs aléatoirement.
2. Chaque joueur attaque une cible de manière stratégique (choix d’attaque et de cible) en suivant les règles.
3. L'ordre d'action des joueurs est aléatoire.
4. Pour chaque attaque, affiche **uniquement** le résultat dans le format demandé.
5. Mets à jour les HP et les cristaux après chaque attaque.
6. Continue le combat tour par tour jusqu’à ce qu’une équipe soit entièrement hors de combat.
7. Précise les équipes au début et précise chaque nouveau tour
8. Utilises des emojis et du formatage aux endroits clefs
9. donne le résultat final avec les HP restants
10. Ne fais rien d’autre.

Commence la simulation.