---
tags:
  - Règles
---
## Ordre d'actions

1. [[Combat#Motivation|Motivation]] (seulement lors du premier tour)
2. [[Combat#Mouvement|Mouvement]]
3. [[Combat#Attaque|Attaque]]

## Motivation

Un joueur peut motiver son équipe (avantage au premier tour) ou déstabiliser l'adversaire (désavantage au premier tour) à l'aide d'une phrase de motivation en début de combat ()
- En début de combat, un joueur peut prononcer une phrase de motivation pour booster son équipe.

- Le MJ peut donner un avantage aux joueurs ou un désavantage aux ennemis selon le sens du discours.

## Mouvement

## Attaque

### Jet pour toucher
>1d20 + Modificateur + Maîtrise >= AC

Le joueur lance 1d20 et y ajoute le modificateur d'attribut correspondant ainsi que sa maîtrise.

Le modificateur d'attribut dépend du type d'attaque

| Modificateur | Utilisation                                                               |
| ------------ | ------------------------------------------------------------------------- |
| Force        | Attaques avec une arme                                                    |
| Dextérité    | Attaques avec une arme ayant la propriété [[Propriétés#Finesse\|finesse]] |
| Mental       | Attaques magiques                                                         |

Le résultat doit être supérieur ou égal à l'AC de la cible pour que des dégâts soient appliqués.

### Jet.s de dégâts
>Dé d'arme + Modificateur + Matériaux + Enchantements + Style
- Chaque arme possède un **dé d’arme** selon son matériau et ses enchantements.

- Le **puissance d’attaque** se calcule ainsi :
	→ Jet de **Dé d’arme**
	→ + **Maîtrise d’arme**
	→ + **Maîtrise de type**
	→ + **Bonus de style**

- On rajoute le **matériau** de l'arme à la puissance d'attaque obtenue pour déterminer les **dégâts infligés**

- Le score doit être **supérieur à l’armure ennemie** pour infliger des dégâts.

- Les **styles de combat** offrent un bonus si réussis, mais retirent ce bonus en cas d’échec.

- La **réussite du style** dépend de son type.

| Élément   | Description                |
| --------- | -------------------------- |
| Dé d’arme | Varie selon arme           |
| Maîtrises | Arme + Type                |
| Style     | Bonus/Malus selon réussite |
| Matériau  | Bonus selon la qualité     |

## Points de fatigue (HP)

- Les **points de fatigue** ne sont pas représentatifs de la vie d'une entité.
	→ S'ils tombent à 0, l'entité n'est pas morte, juste en trop mauvais état pour effectuer des actions directes dans le combat (Attaquer n'est pas possible, mais bouger et activer un piège l'est).

- Les humanoïdes possèdent tous un **maximum de 50 HP** qui se régénèrent avec du repos (pour peu que la personne ait mangé récemment) ou de la magie.

## Défense

- Pour bloquer une attaque, on additionne :
	→ **Matériau de l’armure**
	→ + **Impénétrable**

- Si ce total est **supérieur à l’attaque**, aucun dégât n’est subi.

## Impénétrable

- Les bonus d'impénétrable ne s'appliquent **que sur le type d'attaque lui correspondant**.
→ Si l'armure a impénétrable en Contondant et que l'attaque est Tranchante, le bonus ne s'applique pas.

## Réaction

### 


## Concentration

Le joueur peut passer son tour pour se concentrer.

- **Magie** : +1 par tour (cumulable).

- **Autres compétences** : +2 (non cumulable).

- La compétence **Imperturbable** permet de se déplacer sans perdre le bonus.

## Adrénaline

- S'active si l'une de ces situations se présentent :
	- un allié tombe de fatigue,
	- le joueur tombe en dessous de 10 PV,
	- le combat entre dans une nouvelle phase.

- Bonus :
	→ **+D10 en Maîtrise de Combat**
	→ **+D10 en Force ou Dextérité**

- Malus :
	→ **–D10 en Maîtrise de Magie**

- L’état disparaît :
	- à la fin du combat,
	- sur réussite d’un **D20 Mental + Concentration > 15**

## Bagarre

- Mode simplifié pour les combats amicaux ou de taverne.

- Chaque joueur : **10 PV**, **D4 de dégâts** (Force = ×2 dégâts).

- Deux approches :
	→ **Force** : brutale
	→ **Technique** : précise et stratégique

| Type      | Calcul                                   | Dé  |
| --------- | ---------------------------------------- | --- |
| Force     | Force + Bagarre                          | D20 |
| Technique | Maîtrises (Court + Contondant) + Bagarre | D12 |

- Pour agir, il faut faire un score **> Force + Impénétrable** de l’adversaire.

| Duel                   | Effet                                                      |
| ---------------------- | ---------------------------------------------------------- |
| Force vs Force         | Les deux peuvent infliger des dégâts                       |
| Force vs Technique     | La Technique peut esquiver au lieu d’attaquer              |
| Technique vs Technique | Pierre (Attaquer) / Papier (Esquiver) / Ciseaux (Attraper) |