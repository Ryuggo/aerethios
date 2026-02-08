>AC (Armor Class) = Mobilité d'esquive naturelle
>DR (Damage Reduction) = Réduction des dégâts

	Armure en tissu : [16-21]AC (6AC + 5Mental + 5Sag/Int +[0-5]crystaux) + [0-10] DR
	Armure en cuir : 16AC (6AC + 5Dex + 5Accro) + 25 DR ([2-25] +25% set complet)
	Armure en métal : 6AC (6AC) + 50 DR ([15-40] +25% set complet)

## Equipement
>Détermine l'AC, ce qui permet d'esquiver les attaques.
>AC = Base + Pièces d'armures + Modificateurs (+ Bouclier)

### Armure
>Lorsqu'une armure se fait toucher par sa faiblesse, seul 50% de sa DR est pris en compte.

L'armure se constitue de plusieurs pièces, chacune permettant d'avoir plus de DR, mais réduisant l'AC (le métal en mailles et en plates double cette réduction).

L'AC minimum est 6.

| Pièce         | AC  | Matériaux | Prix main d'œuvre | DR (basée sur les matériaux) |
| ------------- | :-: | :-------: | ----------------: | :--------------------------: |
| Base          | 15  |     -     |                 - |              -               |
| Cape/ Foulard |  0  |     1     |              5 pa |              -               |
| Casque        | -1  |     2     |             10 pa |             20%              |
| Bras d'armure | -1  |     4     |             20 pa |             10%              |
| Plastron      | -2  |     8     |             40 pa |             40%              |
| Jambières     | -2  |    10     |             50 pa |             30%              |

>Exemple : un joueur avec un casque en orichalque (40 DR) aura 11 AC et 8 DR.

Le modificateur utilisé pour l'AC dépend du type de matériaux de chaque pièce.
On ne peut utiliser qu'un seul type de modificateur (le modificateur le plus élevé est pris par défaut).

|            Tissu            | Cuir, Peaux, Écailles, Os et Mailles (métal) | Plate (métal) |
| :-------------------------: | :------------------------------------------: | :-----------: |
| Dextérité<br>(+ Accrobatie) |         Dextérité<br>(+ Accrobatie)          |       -       |
|  + Crystaux (max = Mental)  |                                              |               |

Selon le nombre de pièces utilisant le même type de matériaux (tissu, cuir, métal, ..), le modificateur maximum change et d'autres bonus s'appliquent (sur la DR totale actuelle).

| Nombre de pièces |  1  |  2  |    3    |    4    |
| :--------------- | :-: | :-: | :-----: | :-----: |
| **Modificateur** | +1  | +2  |   +3    |   +5    |
| **Bonus**        |  -  |  -  | +10% DR | +25% DR |

Les enchantements ne s'appliquent que sur des armures complètes d'un même matériaux ou sur des capes/ foulards.

Le joueur peut préciser la partie du corps qu'il attaque s'il n'est pas en combat.

### Boucliers

**Effets**
    - La DR du bouclier ne s'ajoute que si le bouclier fait face à la source de l'attaque (attaque de front/ dans le dos).

| Armure           | AC  | Matériaux | Prix main d'œuvre | DR (basée sur les matériaux) | Force |                         Propriétés                         | Dégats         |
| ---------------- | :-: | :-------: | ----------------: | :--------------------------: | :---: | :--------------------------------------------------------: | -------------- |
| *Buckler*        | -1  |     2     |              5 pa |             25%              |  ---  |               [[Propriétés#Parade\|Parade]]                | 1d4 C          |
| Bouclier         | -2  |     4     |             10 pa |             50%              |  ---  |                            ---                             | 1d6 C          |
| Bouclier d'Estoc | -3  |     6     |             20 pa |             75%              |  14   |               [[Propriétés#Charge\|Charge]]                | 1d6 C<br>1d8 P |
| Pavois           | -4  |     8     |             40 pa |             100%             |  17   | [[Propriétés#Charge\|Charge]]<br>[[Propriétés#Lent\|Lent]] | 1d8 C          |

## Matériaux
>Détermine la DR, ce qui permet de réduire les dégâts reçus.

### Tissus et Fourrures
>Peut s'équiper par dessus une armure comme cape ou foulard.

**Faiblesse**
	Perforant & Tranchant

**Effets**
    + [[Enchanteur#Suraja|Enchantements de Suraja]]
    + Les propriétés d'un tissu ne sont actives que si l'armure ne contient pas de métaux
    + Pendant son tour, le joueur peut convertir des crystaux en AC (1:1, Max = Modificateur Mental). Il perd ce bonus une fois touché

| Matériau    | DR  |  Prix |                Propriétés                 | Poids (kg) |
| ----------- | :-: | ----: | :---------------------------------------: | :--------: |
| Coton       |  2  | 10 pa |    Air = 2 crystaux bonus par attaque     |    0.25    |
| Chanvre     |  2  | 10 pa |    Eau = 2 crystaux bonus par attaque     |    0.25    |
| Lin         |  2  | 10 pa |   Roche = 2 crystaux bonus par attaque    |    0.25    |
| Soie        |  2  | 10 pa |  Lumière = 2 crystaux bonus par attaque   |    0.25    |
| Suède/ Daim |  2  | 10 pa |  Ténèbres = 2 crystaux bonus par attaque  |    0.25    |
| Laine       |  2  | 10 pa |   Foudre = 2 crystaux bonus par attaque   |    0.25    |
| Cachemire   |  2  | 25 pa | Elétistes = 1 crystal gratuit par action  |    0.5     |
| Alpaga      |  2  | 25 pa | Croitistes = 1 crystal gratuit par action |    0.5     |
| Fourrure    |  2  | 40 pa |   Fusion = 1 crystal gratuit par action   |    0.5     |

>Les crystaux bonus par attaque nécessite d'en consommer au moins 1 pour s'appliquer (ex : 1 consommer +2 gratuits).

### Cuirs et Peaux

**Faiblesse**
	Tranchant

**Effets**
    + [[Enchanteur#Kothula|Enchantements de Kothula]]
    + Se répare dans une tannerie

>La rareté varie entre 1 et 5 (Déchet, Commun, Peu commun, Rare, Légendaire)

| Matériau       |     DR     |          Prix |                   Propriétés                    | Poids (kg) |
| -------------- | :--------: | ------------: | :---------------------------------------------: | :--------: |
| Peau           | 2 * rareté | 2 ^ rareté pa | Résiste à [[Conditions#Saignement\|Saignement]] |     1      |
| Cuir (bouilli) | 3 * rareté | 4 ^ rareté pa |     Résiste à [[Conditions#Poison\|Poison]]     |     1      |

### Écailles, Os et Mailles

**Faiblesse**
	Perforant

**Effets**
    + Se répare auprès d'un potionniste (écailles et os)
    - Désavantage en Dextérité (Discrétion)
    - Désavantage en Magies en combat

| Matériau |     DR     |           Prix |                   Propriétés                   | Poids (kg) |
| -------- | :--------: | -------------: | :--------------------------------------------: | :--------: |
| Écaille  | 4 * rareté |  8 ^ rareté pc |           Résistance aux conditions            |    1.5     |
| Os       | 5 * rareté | 10 ^ rareté pc | [[Enchanteur#Ovliin\|Enchantements d'Ovliin]]  |     1      |
| Mailles  | 50% Métal  |      50% Métal | [[Enchanteur#Nirina\|Enchantements de Nirina]] | 50% Métal  |
|          |            |                |           Pas de pré-requis en Force           |            |

### Métaux

**Faiblesse**
	Contondant

**Effets**
    + [[Enchanteur#Nirina|Enchantements de Nirina]]
    + Se répare dans une forge/ avec la magie de métal
    - Dextérité (Discrétion) impossible
    - Magies impossibles en combat
    - Nécessite +1 Force pour chaque pièce d'équipement en métal à partir de la deuxième pièce (Ex : 2pièces= +1, 4p = +3)

| Matériau   | DR  |  Prix |                    Propriétés                    | Poids (kg) |
| ---------- | :-: | ----: | :----------------------------------------------: | :--------: |
| Fonte      | 15  |  2 pa |                       ---                        |    1.5     |
| Fer        | 18  | 10 pa |                       ---                        |     1      |
| Bronze     | 21  | 25 pa |                       ---                        |    1.5     |
| Acier      | 24  | 50 pa |                       ---                        |     1      |
| Titane     | 27  |  1 po |                       ---                        |    1.5     |
| Mythril    | 30  |  5 po | Dextérité (Discrétion) possible avec désavantage |     1      |
| Palladium  | 35  |  7 po | Magies (Croititiste) possibles avec désavantage  |     2      |
| Adamantite | 35  |  7 po |   Magies (Élétiste) possibles avec désavantage   |     2      |
| Orichalque | 40  | 10 po |                       ---                        |    2.5     |
