# Missing Timing

Certain card effects (that includes both Monster/Spell/Trap cards) can "miss timing".

To put it simply if a card effect's activation condition says "When ..." this automatically means that 
in order for the activation condition to be satisfied and activate the card/effect the condition described 
**must** be the last thing that happens in the Chain.

If a card effect's activation condition says  "If ..." this means that no matter if the activation 
condition was or wasn't the last thing to happen in the chain, the effect can still be activated in 
a new chain once the current chain resolves.

## Example 1: "When" not missing the timing

1. Turn player activates Call of the Haunted during their Main Phase  in order to summon Dark Magician 
of Chaos (Chain Link 1). 

Dark Magician of Chaos text reads:

>**When** this card is Normal or Special Summoned: You can target 1 Spell Card in your Graveyard; add that 
>target to your hand. Banish any monster destroyed by battle with this card. If this face-up card would 
>leave the field, banish it instead.

1. Chain Link 1 resolves: Dark Magician of Chaos has been Special Summoned, no other effects need to resolve 
so Dark Magician of Chaos' trigger effect can activate as Chain Link 1 on a new Chain.


## Example 2: "When" missing the timing

1. Opponent activates Mystical Space Typhoon targeting turn player's set Call of the Haunted. (Chain Link 1)
2. Turn player activates Call of the Haunted, in order to summon Dark Magician of Chaos. (Chain Link 2)

Dark Magician of Chaos text reads:

>**When** this card is Normal or Special Summoned: You can target 1 Spell Card in your Graveyard; add that 
>target to your hand. Banish any monster destroyed by battle with this card. If this face-up card would 
>leave the field, banish it instead.

1. Chain Link 2 resolves: Dark Magician of Chaos has been Special Summoned, but Chain Link 1 effects still need to resolve. Dark Magician of Chaos' trigger effect cannot activate at this time, so it missed the activation timing.
2. Chain Link 1 resolves: Mystical Space Typhoon destroys Call of the Haunted.


## Example 3: "If" not missing the timing

1. Opponent activates Mystical Space Typhoon targeting turn player's set Call of the Haunted. (Chain Link 1)
2. Turn during their Main Phase, as Chain Link 1, in order to summon Sacred Crane. (Chain Link 2)

Sacred Crane text reads:

>**If** this card is Special Summoned: Draw 1 card.

1. Chain Link 2 resolves: Sacred Crane has been Special Summoned, but Chain Link 1 effects still need to resolve.
2. Chain Link 1 resolves: Mystical Space Typhoon destroys Call of the Haunted.

After the above chain resolves Sacred Crane's effect trigger condition has been satisfied, so it 
activates in a new Chain as Chain Link 1.
