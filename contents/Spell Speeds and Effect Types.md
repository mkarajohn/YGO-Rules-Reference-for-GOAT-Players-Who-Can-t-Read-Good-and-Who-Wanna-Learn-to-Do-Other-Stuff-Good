# Spell Speeds and Monster Effect Types

## Monster Effect Types

The game has the following Monster effect types:

### Continuous effects

> [!NOTE]
> **Does not create a Chain Link**

These are effects that start applying immediately once the monster is successfully summoned 
("successfully" means its summon was not negated, otherwise it was successfully summoned, even if it 
was immediately destroyed).

### Trigger effects

> [!NOTE]
> **Creates a Chain Link**

These are Spell Speed 1 effects that activate when a specific condition is met (they "trigger"). 
They can be either *mandatory* or *optional* (You can tell when an effect is optional if it includes 
the words "You can"). Flip Effects are a special kind of Trigger Effect. Trigger effects _can_ 
activate during the non-turn player's turn, depending on the trigger condition of the card.

> [!IMPORTANT] 
>Some Trigger effects [can miss timing](./Missing%20Timing.md)

### Ignition effects

> [!NOTE]
> **Creates a Chain Link**

These are Spell Speed 1 effects that the turn player can choose to activate (think of it as 
"turning the ignition" of a car) during their Main Phase. 

### Quick effects

> [!NOTE]
> **Creates a Chain Link**

These are Spell Speed 2 effects that are very similar to ignition effects with the exception that 
they can be activated whenever a Spell Speed 2 effect can be activated. (AFAIK, in GOAT format only 
Kuriboh has a Quick Effect) 

## Spell/Trap Effect Types

Much like Monster effects, Spell/Trap effects also have effect types, pretty much equivalent to these of Monster effect types:

* Continuous effects - Found in Continuous Spell/Trap cards, Field Spell cards and Equip Spell cards
* Trigger-like effects - Found in Continuous Spell/Trap cards
* Ignition-like effects - Found in Continuous Spell cards
* Quick-like effects - Found mostly in Trap cards

Same things apply, as in Monster effects types.


## Spell Speed Tiers

The term "Spell Speed" describes when you can activate certain cards or effects. There are 3 tiers of Spell Speed in the game:

### Spell Speed 1

Includes Normal, Continuous, Equip, Field and Ritual Spell cards, Trigger and Ignition Monster effects, Trigger-like and Ignition-like Spell/Trap effects.

* Spell Speed 1 effects can only start a Chain and they cannot be chained to Spell Speed 2 and Spell Speed 3 effects.
* If 2 or more Spell Speed 1 effects happen simultaneously then they do chain with each other in the following order (also known as "**SEGOC**" - Simultaneous Effects Go On Chain):
  1. **Turn player's mandatory effects first**. If there's more than 1 the turn player chooses the order.
  2. **Non-turn player's mandatory effects**. If there's more than 1 the non-turn player chooses the order.
  3. **Turn player's optional effects**. If there's more than 1 the turn player chooses the order.
  4. **Non-turn player's optional effects**. If there's more than 1 the non-turn player chooses the order.

> [!WARNING]
>In Goat Format, simultaneous effects work exactly as stated above, with one additional caveat: 
> when two effects were triggered at different times, the earlier trigger(s) must be placed on the 
> Chain before the later ones. So in other words, if two mandatory effects are triggered in sequence, 
> whether as part of a Chain resolution or through some other action, you will construct the 
> resulting Chain by going through the "steps" above for each "time" an effect(s) was triggered. 
> Because of specific rule quirks governing the activation of optional trigger effects (missing the timing), 
> this will basically only ever come up in “steps” 1 and 2. 
>
>Example 1: Player A tributes their Sangan to Tribute Summon Thestalos the Firestorm Monarch. 
> In the resulting Chain, Sangan’s mandatory Trigger Effect will be Chain Link 1, and Thestalos’s 
> mandatory Trigger Effect will be Chain Link 2.
>
>Example 2: Player A activates Soul Exchange, targeting Player B’s Sangan. Player A Tributes Player B’s 
> Sangan to Tribute Summon Thestalos the Firestorm Monarch. In the resulting Chain, Sangan’s mandatory 
> Trigger Effect will be Chain Link 1, and Thestalos’s mandatory Trigger Effect will be Chain Link 2.

### Spell Speed 2

Includes Quick Play Spell cards, Normal and Continuous Trap cards, Quick Monster effects, Quick-like Spell/Trap card effects.

* Spell Speed 2 effects can start or add to a Chain and they can be chained to Spell Speed 1 and Spell Speed 2 effects.

### Spell Speed 3

Includes Counter Trap cards.

* Spell Speed 3 effects can only add to a Chain and they can be chained to Spell Speed 1 Spell Speed 2 and other Spell Speed 3 effects.
