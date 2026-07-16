
# Rolling Dice

!!! warning "Developers:"
    if you are building atop MUSE, it should be noted that any changes, omissions, or additions to the rules are entirely personal preference. Even the names of every mechanic in this framework can be altered (though we advise against this for developers who'd like their players to use the MUSE [Character Sheet App](https://app.muserpg.com)).


The **9 TRAITS** are at the heart of MUSE, their scores determining how many dice a character rolls for each action taken. That being said, rolling can be entirely skipped when it's deemed unnecessary. *For example, if an enemy is standing directly in front of you, unobscured, and in broad daylight, you don't need to roll Awareness to see them.*

- **AWARENESS:** Notice details others miss. *Spot the glint of a tripwire before your boot hits it.*
    
- **CHARM:** Influence through personality and presence. *Convince the guard their shift ended an hour ago.*
    
- **ENDURANCE:** Withstand physical and mental punishment. *Stay conscious when the blast throws you into a wall, or something attempts to invade your mind.*
    
- **MIGHT:** Apply raw physical strength. *Bend the cell bars wide enough to slip through.*
    
- **POWER:** Command magic or technology. *Overload the security grid or dispel the ward blocking your path.*
    
- **SAGE:** Draw on knowledge or experience. *Recognize the poison from its smell before anyone drinks.*
    
- **SUBTERFUGE:** Move unseen and deceive. *Lift the keyring while shaking the captain's hand.*
    
- **SURVIVAL:** Heal wounds and manipulate your environment. *Stitch a gash closed or fashion climbing rope from torn sheets.*
    
- **SWIFTNESS:** React with speed and agility. *Dive behind cover as the archer's fingers release.*


## Successes & Failures

Every action is resolved by rolling six-sided dice *(commonly called a d6).* A character's Trait scores determine how many dice they roll for any given action. *For example, if your Awareness is 5, then you would roll 5 dice.* **However**, a Trait score cannot be raised higher than 10 dice. Upon reaching a Trait score of 10, that Trait is considered **Mastered** and gains Exploding 6s *(elaborated on in [Leveling Up](./charactercreation.md#mastered-traits))*.

Bonuses from relevant [Items](./charactercreation.md#items-weapons-armor) and [Talents](./charactercreation.md#talents) can push the total number of dice rolled above 10, but the Trait score itself cannot exceed 10.

Each roll of a **4, 5, or 6** counts as a success. However, **each roll of 1 subtracts a success** *(though a character can never have negative successes).* When a roll uses a Path's Key Trait a roll of 1 does not subtract a success. For most Actions without major conflict, rolling at least one success means you accomplish your goal. *For example, shooting an apple off of another's head.*

!!! success "There is never a set DC or target value."
    All rolls are either made to attain successes, or to attain more successes than another.

When one or more characters take an action to assist another, the character receiving help adds 1 die to their roll per assisting character.

However, when a character takes any action *against* another *(inside or outside of combat)*, both characters roll **OPPOSING TRAITS**. Whoever rolls more successes wins. *For example, a player trying to deceive a guard could roll Charm against the guard's Awareness. If the player rolls 2 successes and the guard rolls 1, the deception works.*

!!! success "In the Event of a Tie"
    it is generally considered good practice for both parties to roll again. That being said, some GMs may prefer for ties between a Player and NPC to always go to the player.

Below is an example of Traits and their Opposing Traits:

| Trait | Opposing Trait(s) |
| :-- | :-- |
| Awareness | Charm/ Subterfuge |
| Charm | Awareness/ Endurance/ Power |
| Endurance | Charm/ Might/ Power/ Swiftness |
| Might | Endurance/ Power/ Swiftness |
| Power | Endurance/ Power/ Swiftness |
| Sage | Charm/ Power/ Subterfuge |
| Subterfuge | Charm/ Power/ Subterfuge |
| Survival | Charm/ Power/ Subterfuge |
| Swiftness | Might/ Power/ Subterfuge |


## Challenges

!!! success "To keep resolutions simpler"
    some GMs may prefer to play without Challenges entirely. However, they can be employed to create more compelling and dynamic play.

When attempting any task where failure has real consequences, the GM may declare it a **CHALLENGE**. When facing a Challenge, both the player and GM roll the same number of dice. The player rolls the Trait relevant to the action, while the GM rolls an equal number of dice representing the difficulty. Whoever rolls the most successes determines the outcome. If both sides roll the same number of successes, the tie automatically goes to the player.

*For example, if you're disarming a trap with 5 dice in Subterfuge, your GM also rolls 5 dice. Whoever gets more successes determines whether or not the bomb can be disabled.*


## Overexertion

Overexertion is a gamble that pushes a character past their limits. After a failed roll, a character can **OVEREXERT** to immediately re-roll all the dice from that attempt. On success, the scene continues without penalty. On failure, the character loses one die from the Trait used until the next session *(or 1d6 days for asynchronous games)*. *For example, if you fail an Overexertion roll with a Might of 5, you can only roll 4 dice for Might until the penalty ends.*

You can also Overexert after a successful roll to gain more successes, adding your original successes to any gained from Overexerting.

> **GM:** There's this huge cliff in your way. You'll need to scale it to keep going. Can everyone roll Might?
> 
> *(Teddie's dice show 2, 3, and 1)*
> 
> **GM:** Oof! No luck there. You can’t seem to find a grip.
> 
> *(Teddie uses Overexertion for another try. This time he rolls 6, 4, and 6)*
> 
> **GM:** Nice comeback, forget about what I said. You mustered all your strength and powered your way right up!


## Scenes & Roleplay

When not in combat, play flows through **SCENES**, moments of narrative focus where characters make meaningful choices. A Scene ends when the immediate situation resolves, or when the party is ready to move on. While GMs usually begin new scenes, any player can request one. The GM will frame where you are, who's present, and what's happening, but Scenes belong to everyone at the table present for them.

When time passes without dramatic tension *(traveling between towns, gathering supplies, training, etc.)* the GM can call for a **MONTAGE**. Each player describes one thing their character does during this period, and no rolls are needed unless something goes wrong.

Scenes end naturally when the immediate tension resolves, when the party moves on to a new location, or when the GM calls for a new Scene to keep momentum. If a Scene drags, anyone at the table can suggest moving forward.


## Combat

Characters find their place in **INITIATIVE** by rolling 1d6 + their Swiftness score. The highest total acts first, followed by the next, and so on in descending order. *For example, if your Swiftness is 5 and you roll a 4, your Initiative is 9. The next player, who rolled an 8 goes after you, and so on.*

On a character's turn they can take 2 Actions. These Actions can be used to move, attack, or otherwise interact with the environment. Additional Actions are attained every 10 Levels, as seen in [Leveling Up](./charactercreation.md#leveling-up).

When two or more characters roll the same Initiative, they enter **SHARED COMBAT** and, as one might suspect, share a turn. Characters in a Shared turn can act in any order they choose *(one action after another, one character taking all their Actions first, etc.)*. Characters can also give some or all of their Actions to another character in ther shared turn if they're unable to act.

Enemies can only enter Shared Combat with other enemies, not with player characters or their allies.

### Rounds & Encounters

Combat plays out in **ROUNDS**, where each character takes their turn in order. A Round ends when all players and GM-controlled characters have acted. Multiple Rounds form an **ENCOUNTER**; which constitutes the entire battle from start to finish. An Encounter ends when the player characters win, run away, or fall in battle.

> **GM:** A bunch of bandits are blocking the road! They're drawing their weapons. Roll for Initiative!
> 
> *(The players roll Initiative. Luis gets a 7, Claud lands a 9, and Audi gets a 5. Claud's in the lead, so they act first.)*
> 
> **GM:** These bandits are coming in hot! What's your move?
> 
> **Claud:** I'm gonna try to bash them back with my shield!
> 
> *(Claud rolls their Might dice and gets two successes.)*
> 
> **GM:** Alright, I’m going to roll the Bandit’s Swiftness to see if he can dodge that, and… NOPE, you send that bandit stumbling and deal two points of damage. Luis, your turn!
> 
> **Luis:** Let me try sweet-talking them into backing down.
> 
> *(Luis rolls his Charm dice and gets a 2 and a 3.)*
> 
> **GM:** Tough luck, these guys aren't in a chatty mood.
> 
> **Audi:** I'm gonna zip behind them so I can attack on my next turn.
> 
> *(Audi rolls their Swiftness dice and lands a 6 and a 3.)*
> 
> **GM:** Sweet moves! You slip right behind them!


### Damage & Healing

A character's fighting style determines which Trait they use in combat: Might for melee attacks, Swiftness for ranged attacks, and Power for magical or technology based attacks. Before making any roll, each character should declare their intent. Are they attempting to Deal Damage? Impose a Tribulation? Heal themselves or another? Intentions cannot be switched after rolling.

When **Dealing Damage**, each success rolled deals 1 point of damage, regardless of the means of attack *(though this can be increased via Talents)*.

When **Imposing Tribulations**, the target rolls an Opposing Trait to resist the attack. If the attacker's roll has more successes than the target's, the target gains the intended Tribulation.

When attempting to **Heal**, a Survival roll can be used to restore Life Points to a character or an ally close to them. Add the number of successes rolled to their Life Points. A character can heal once per Action in combat, and once per Scene outside of combat.

When attempting to attack or heal multiple targets, roll 1d6. The result reflects how many characters are affected, each taking the same Damage/ Healing, rounded down.


### Dodge, Endure, Counter

When any character is attacked, they can choose how to respond: **DODGE** to avoid the attack entirely, **ENDURE** to reduce damage, or **COUNTER** to strike back. Unless affected by a Tribulation or other complication that would prevent them from moving, a character being attacked must always be allowed to perform one of the above, regardless of the order set by Initiative.

To **Dodge**, characters make an Opposing Swiftness roll against their attacker's roll. If they roll more successes, they avoid the attack completely and take no damage.

If a character finds themselves unable to dodge, they can roll to **Endure** by making an Opposing Endurance roll. If the attacked character is successful, damage is halved *(rounded up). For example, if an attack would deal 4 damage, Enduring reduces it to 2.*

For those who would prefer to retaliate, characters can roll to **Counter**, using their Opposing Roll to attack with Might, Swiftness or Power. If the attacked character rolls more successes than their attacker, they redirect the damage to their attacker halved *(rounded down)*. The attacker, however, can also Counter their Counter, creating a back-and-forth exchange. This continues until someone fails to Counter or chooses to Dodge or Endure instead.


### Distance

Distance isn't measured in exact feet or meters but in the simple terms of **CLOSE**, **NEAR**, and **FAR**. Outside of combat, characters may move freely without calculating distance.

!!! warning "A Note for Devs:"
    Settings which expand upon these rules can introduce their own mechanics for overland travel separate from these metrics.

In combat, characters can:

- Move to anything Close without taking an action
- Move to anything Near in a single action
- Move to anything Far with two Actions.

| Distance | Example/ Reference |
| :-- | :-- |
| Close | A few steps away _(5–15 Feet or 1–5 Meters)_ |
| Near | Across the room _(20–40 Feet, 6–12 Meters)_ |
| Far | Across the field _(45–60 Feet, 14–20 Meters)_ |


## Tribulations

Tribulations are negative conditions that can affect a character, limiting their abilities or causing ongoing harm until they shake them off. A character might suffer Tribulations from Powers, Weapons, hazards in the environment, etc.

The GM can declare a character has been afflicted by a Tribulation when:

- They roll no successes on a roll where failure would logically hurt or hinder them. *For example, failing an Endurance roll as debris crashes down upon you could inflict the Unconscious Tribulation.*
    
- They face harsh conditions or take heavy damage. *For example, traveling through extreme heat could inflict the Tired Tribulation, or taking 5+ damage in one hit could cause the Bleeding Tribulation.*
    
- An enemy lands an attack meant to cause a specific condition. *For example, a venomous snake bite could cause the Poisoned Tribulation, a hypnotic gaze could cause the Charmed Tribulation, or an ice spell could leave a character with the Frozen Tribulation.*

Most Tribulations fade naturally after **FIVE ROUNDS**, except for Bleeding, Burning, Tired, and Unconscious, which last until addressed.

A character cannot take the same Tribulation twice while the first instance is still active, but different Tribulations can stack. To remove a Tribulation, roll the **Recovery Trait** at the start of their turn. This uses an Action. If another character's Actions caused your Tribulation, including those under the control of the GM, treat this as an Opposing Trait roll.

| Tribulation | Example Imposing Trait | Recovery Trait | Description |
| :-- | :-- | :-- | :-- |
| Bleeding | Might/ Power/ Swiftness | Survival | When a character's turn starts, they lose 1d6 Life Points. Any action not spent trying to stop Bleeding causes 1 more Life Point of damage. |
| Burning | Power | Swiftness | At the start of each turn while actively Burning, a character takes 1d6 damage. Any action not spent trying to extinguish the flames causes an additional 1d6 of damage. |
| Charmed | Charm | Awareness | The affected character cannot attack their charmer. Each Round, they must follow one reasonable command the charmer gives them. |
| Enfeebled | Power | Endurance | A character rolls half their Might/ Swiftness dice *(rounded up)*. |
| Frozen | Power | Endurance | A character cannot move or take any Actions *(including speaking)*. |
| Grappled | Endurance/ Might | Might/ Swiftness | A character cannot Dodge, Counter, or take any action except Recovery Trait rolls. |
| Impaired | Might/ Power | Endurance | A character is Blinded, Deafened, Muted, or all three. Any roll relying on an impaired sense automatically fails. |
| Intimidated | Charm/ Subterfuge | Endurance | A character cannot attack what frightens them. The source of their fear gains two additional dice to every roll made against them. |
| Poisoned | Might/ Power/ Swiftness | Survival | Until cured, a character rolls half their Endurance dice *(rounded up)*. Their Current Life Points are also halved, and they lose 1 Maximum Life Point every session *(or 1d6 days for asynchronous games)* until cured or killed. |
| Stunned | Might/ Power | Endurance | A character loses their next action. If they have no Actions remaining in the current Round, they lose their first action the next Round instead. They can only move to things Close, and cannot Dodge, Endure, or Counter. |
| Tired | Power | N/A | A character can only roll half of any Trait’s dice *(rounded up)*. To recover, they must rest for 1d6 Rounds. During these Rounds, they can only take defensive Actions but no offensive or movement Actions. Outside of combat, they must rest for one entire Scene. |
| Unconscious | Endurance/ Might/ Power/ Swiftness | Awareness | A character cannot take any action. Another character can try to wake them, giving them +1 Awareness die per assisting character. |


## Death

When a character's Life Points are reduced to 0 they gain the Unconscious Tribulation and are considered **DYING**. At the start of each turn while dying, both the character and the GM roll Endurance as a Challenge. Whoever rolls more successes wins that round. If both sides roll the same number of successes, re-roll.

The GM should keep a running count of successes and failures. The first total to reach three determines the character's fate. If the character succeeds three times, they immediately regain consciousness at 1 Life Point and gain the Tired Tribulation. If the character fails three times, they die permanently.

**HOWEVER**, if at any point a character's Life Points exceeed the rating of their Endurance score *(for example, -6 Life Points when your Endurance is 6)*, the character dies instantly.

Allies can always take Actions to Heal the dying. Any healing that restores a character to 1 Life Point immediately ends the dying state, and they regain consciousness with the Tired Tribulation as mentioned above.