>Le type d'arme ainsi que ses matériaux vont influencer les bonus, malus et enchantements que celle-ci peut posséder.

	Dégâts max :
		Courte : ([1-16] + [8-16](ori)) = [9-32] x2(crit) = [18-64]
		1 Main : ([1-16] + 10(pui)) + [8-16](ori) = [19-42]
		2 Mains : ([1-16] + 2x20(pui)) + [8-16](ori) = [49-72]
		Haste : ([1-16] x 2) + [8-16](ori)) = [10-48]
		Arc : [1-8] x5 + Munitions = [5-40]
		Arbalète : 8 x5 + Munitions = 40
		Fusil : 20 x5 + Munitions = 100

## Dégâts

| Catégorie                     | Prix main d'œuvre | Dégâts                   | Modificateur          |            Propriétés             |   Matériaux |
| ----------------------------- | ----------------: | ------------------------ | --------------------- | :-------------------------------: | ----------: |
| Courte                        |              5 pa | Dé                       | Dextérité\|Force      | [[Propriétés#Critique\|Critique]] |  1 Matériau |
| 1 Main                        |             10 pa | Dé + Puissance           | Dextérité\|Force      |    [[Propriétés#Léger\|Léger]]    | 2 Matériaux |
| 2 Mains                       |             20 pa | Dé + (2 x Puissance)     | Force\|Dextérité      |                ---                | 3 Matériaux |
| Haste                         |             40 pa | Dé x 2                   | Force\|Dextérité      |   [[Propriétés#Portée\|Portée]]   | 5 Matériaux |
| Distance<br>(Arcs)            |  5 x Puissance pa | Puissance x Modificateur | Dextérité\|Perception |                ---                |           - |
| Distance<br>(Arbalètes)       | 20 x Puissance pa | Puissance x Modificateur | Perception            |     [[Propriétés#Lent\|Lent]]     |           - |
| Distance<br>(Fusils & Canons) |  1 x Puissance po | Puissance x Modificateur | Perception            | [[Propriétés#Instable\|Instable]] |           - |

- Le dé de dégâts change selon les enchantements,
- le bonus est déterminé par le poids de l'arme,
- la puissance est généralement déterminée par la taille de l'arme.

### Enchantements

Enchanter une arme permet d'augmenter son dé de dégâts.

Si une arme est en métal, seul les [[Enchanteur#Nirina|Enchantements de Nirina]] sont efficaces.

Si une arme est en os, seul les [[Enchanteur#Ovliin|Enchantements d'Ovliin]] sont efficaces (en plus de lui ajouter un effet magique).

|     Enchantement      | Base |   +1   |   +2   |   +3   |   +4   |   +5    |
| :-------------------: | :--: | :----: | :----: | :----: | :----: | :-----: |
| **Réussite normale**  | 1d6  |  1d8   |  1d10  |  1d12  | 2d6 +2 | 2d6 +4  |
| **Réussite critique** |  -   | 1d6 +2 | 1d6 +4 | 1d6 +6 | 1d6 +8 | 1d6 +10 |

### Puissance

#### Mêlée

Une arme à 1 ou 2 Mains peut être modifiée pour altérer ses dégâts.

|            | Léger                             |     Normal      | Lourd                       | Colossal                                     |
| ---------- | :-------------------------------- | :-------------: | :-------------------------- | :------------------------------------------- |
| Matériaux  | -1 Matériau                       |       ---       | +1 Matériaux                | x3 Matériaux                                 |
| Bonus      | Modificateur de Force + Dextérité |    Bonus = 1    | Modificateur de Force       | 20                                           |
| Prérequis  | Dextérité > 14 pour s'en servir   |       ---       | Force > 14 pour s'en servir | Force > 17 pour s'en servir                  |
| Catégorie  | Devient une arme à 1 Main         | 1 Main\|2 Mains | Devient une arme à 2 Mains  | Devient une arme à 2 Mains                   |
| Propriétés | -                                 |       ---       | -                           | [[Propriétés#Lent\|Lent]] sauf si Force > 19 |

#### Distance

|             |            Petit            | Normal |           Grand           |
| ----------- | :-------------------------: | :----: | :-----------------------: |
| Arcs        |             1d4             |  1d6   |            1d8            |
| Arbalètes   |              4              |   6    |             8             |
| Armes à feu |              5              |   10   |            20             |
| Propriétés  | [[Propriétés#Léger\|Léger]] |  ---   | [[Propriétés#Lent\|Lent]] |

### Munitions

Les munitions utilisées avec une arme à distance possèdent leur propre propriété.

D'autres [[aerethios/docs/Jeu/Règles/Combat/Armes#Matériaux|matériaux]] peuvent être utilisés comme munitions mais n'offrent que des propriétés de VS.

| Matériaux  | Arme             | Prix/ unité |                     Propriétés                      |
| ---------- | ---------------- | ----------: | :-------------------------------------------------: |
| Tissu      | Arcs & Arbalètes |        1 pa |                      Enflammé                       |
| Obsidienne | Arcs & Arbalètes |        5 pa |                        10 T                         |
| Plomb      | Armes à feu      |       10 pa |           [[Afflictions#Poison\|Poison]]            |
| Crystaux   | Tout             |        1 po | [[Afflictions#Surcharge\|Surcharge]]<br>5 munitions |

En fonction de la façon dont les munitions sont créées, des effets additionnels peuvent s'ajouter.

| Type                                | Arme                        |                         Propriétés                         | Nombre de munition/ matériau |
| ----------------------------------- | --------------------------- | :--------------------------------------------------------: | :--------------------------: |
| Basique<br>(flèche, carreau, balle) | Tout                        |                            ---                             |           2d4 +12            |
|                                     | Arcs & Arbalètes            |                                                            |                              |
| Boulet                              | Armes à feu (Grand)         |    La cible touchée est [[Conditions#Couché\|Couchée]]     |              1               |
| Shrapnel                            | Armes à feu (Normal\|Grand) | [[Propriétés#Lacération\|Lacération]]<br>Portée Max = 10ft |            2d4 +6            |
| Potion                              | Armes à feu                 |                Zone d'effet de 5ft de rayon                |              1               |

## Matériaux
>La propriété VS double le dé de dégâts lorsque l'attaque touche le bon type de cible.

### Principaux

**Effets**
    + Se répare dans une forge/ avec la magie de métal

| Matériau   |   Prix/ unité |    Dégâts    |          Propriétés           | Poids/ unité |
| ---------- | ------------: | :----------: | :---------------------------: | :----------: |
| Os         | 5 ^ rareté pa | rareté (1-5) | Enchantements élémentaires x2 |     1 kg     |
| Fonte      |          2 pa |      0       |        VS Nécrophages         |    1.5 kg    |
| Fer        |         10 pa |      1       |           VS Bêtes            |     1 kg     |
| Bronze     |         25 pa |      2       |        VS Insectoides         |    1.5 kg    |
| Acier      |         50 pa |      3       |          VS Mutants           |     1 kg     |
| Titane     |          1 po |      4       |        VS Invocations         |    1.5 kg    |
| Mythril    |          5 po |      5       |        VS Elementaires        |     1 kg     |
| Palladium  |          7 po |      6       |           VS Anges            |     2 kg     |
| Adamantite |          7 po |      7       |         VS Draconides         |     2 kg     |
| Orichalque |         10 po |      8       |           VS Démons           |    2.5 kg    |

### Revêtements
>Le revêtement retire les propriétés du matériau principal et applique le sien à la place.

| Matériau  | Prix/ unité |  Propriétés   | Poids/ unité |
| --------- | ----------: | :-----------: | :----------: |
| Cuivre    |       50 pc |  VS Plantes   |     2 kg     |
| Argent    |       50 pa |  VS Hybrides  |     2 kg     |
| Sombronce |        1 po |  VS Naturels  |     1 kg     |
| Electrum  |       10 po |  VS Magiques  |     2 kg     |
| Or        |       50 po | VS Mythiques  |     4 kg     |
| Platine   |      500 po | Vs Humanoides |     3 kg     |