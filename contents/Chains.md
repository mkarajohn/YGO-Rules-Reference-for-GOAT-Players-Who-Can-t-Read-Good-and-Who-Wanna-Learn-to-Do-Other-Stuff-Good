# Chains

A "Chain" is a queue/stack of player actions ("Chain Links") that start _resolving_ in reverse order 
(in a first-in-last-out fashion) when there are no more actions added by either player to the Chain.

While the actions in a Chain resolve ("while the Chain resolves") no more new actions can be added to it.

**Example**

1. Player A does Action A.
2. Action A becomes the 1st action (Chain Link 1) in the Chain (stack)
3. Player B does Action B in response to Action A
4. Action B becomes the 2nd action (Chain Link 2) in the Chain.
5. Neither player wants to add any more actions to this Chain.
6. The Chain starts resolving in reverse order and no new actions (Chain Links) can be added to it at this point
7. Action B (Chain Link 2) resolves first
8. Action A (Chain Link 1) resolves second

>[!tip]
>"Starting a Chain" is another way to say that an action becomes Chain Link 1.

## Actions that become Chain Links

* Activating Spell/Trap cards
* Activating Monster/Spell/Trap card effects

## Actions that do not become Chain Links

* Summoning a Monster on its own and not by other card effects (e.g. Monster Reborn)
* Setting a Monster
* Setting Spell/Trap cards
* Change battle position of a Monster
* Declaring an attack
* Changing turn Phases

>[!NOTE]
> While none of the above actions start a chain, players _can start_ a Chain as a response to one 
> of the above actions happening