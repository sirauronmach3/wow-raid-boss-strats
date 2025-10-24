# [Amber-Shaper Un'Sok](<https://www.wowhead.com/mop-classic/guide/raids/amber-shaper-unsok-heart-of-fear-strategy-abilities>)
*Video guides*
- *[WowHead](<https://www.youtube.com/watch?v=82s_NAFlKLw>)*
- *[Fatboss](<https://www.youtube.com/watch?v=UzfCS6_bYEA>)*

This boss will summon 3 types of adds: [Constructs](#mutated-construct-construct), [Ambers](#living-amber-amber), and a [Monstrosity](#amber-monstrosity-monstrosity).

A core component of this boss is using the vehicle controls of the [Mutated Construct](#mutated-construct), which everyone will experience being inside of at some point. During phase 3, there will no longer be an escape mechanic from the vehicle.
#### [Mutated Construct](<https://www.wowhead.com/mop-classic/npc=62701/mutated-construct>) *(Construct)*
<img src="https://wow.zamimg.com/modelviewer/mists/webthumbs/npc/74/46154.webp" width="200">

Mutated Construct has 2 resources, its health and its willpower (You can think about it like energy). 

The vehicle starts with 100 willpower and loses 2 willpower per second. Giving you a max of 50 sec in the vehicle without [consuming](#consume-amber) a [pool](#burning-amber) or casting [Struggle for Control](#struggle-for-control). Assuming that you will need to cast [Struggle for Control](#struggle-for-control) every 10 seconds, [***you can stay in your construct for 34 seconds***](<MonstrousConstructWillpower.md>).

If you reach 0 willpower, you die and the vehicle becomes sentient as an additional add. An ***Uncontrolled Construct***

- ##### [Smash](<>)
  - Melee attack doing 120k damage
  - GCD
  - Strat:
    - This is your filler

- ##### [Amber Explosion](<https://www.wowhead.com/mop-classic/spell=122398/amber-explosion>)
  - Cast made by the vehicle itself, it will start doing this with or without player action.
  - 2.5 sec cast
  - 175k Raid damage
  - Can be interrupted by [Struggle for Control](#struggle-for-control)
  - Strat:
    - Everyone: Interrupted this every time withe [Struggle for Control](#struggle-for-control)

- ##### [Amber Strike](<https://www.wowhead.com/mop-classic/spell=122389/amber-strike>)
  - Strike which deals 350k damage to target
  - 6 sec cooldown
  - Applies [Destabilize](#destabilize) to target
  - Interrupts [Monstrosity](#amber-monstrosity-monstrosity) casting [Amber Explosion](#amber-explosion-1)
  - Strat:
    - Everyone: Interrupting the [Monstrosity](#amber-monstrosity-monstrosity)'s [Amber Explosion](#amber-explosion-1) is the top priority.

- ##### [Struggle for Control](<https://www.wowhead.com/mop-classic/spell=122395/struggle-for-control>)
  - Stuns the vehicle for 0.5 sec
  - Vehicle takes 100% more damage for 5 sec
  - Expends 8 Willpower
  - Strat:
    - Driver: Use this ability to interrupt [Amber Explosion](#amber-explosion). *** This is priority, only behind interrupting [Monstrosity](#amber-monstrosity-monstrosity)'s [Amber Explosion](#amber-explosion-1)

- #### [Consume Amber](<>)
  - When touching a pool, restore 20 willpower
  - Heals Vehicle for 2.1m Health

- ##### [Break Free](<https://www.wowhead.com/mop-classic/spell=123060/break-free>)
  - Exits the vehicle
  - Requires the vehicle to be <20% health
  - Costs 8 Willpower

- ##### [Destabilize](<https://www.wowhead.com/mop-classic/spell=123059/destabilize>)
  - Increases damage done to target by 10% for 15 sec
  - This effect stacks
    - (I don't know what the cap on stacks is, assume it is unattainable)
  - Strat:
    - Keep this up on Amber-Shaper for the entire fight. This is the skill which will dramatically increase the rate at which you move through this fight.

- Strategy/priority List when inside the [Construct](#mutated-construct-construct):
  - Mind your willpower, you need 8 to use [Break Free](#break-free), 
    - ***never let your willpower drop below 10***.
  - Be below 20% health.
    - When you are above 20% health, communicate that to the raid. Raid lead will direct dps to you. If he doesn't communicate again, until he at least acknowledges.
    - "My construct is above 20"
    - "My willpower is low, I need my health down"
  - Use [Amber Strike](#amber-strike) on cooldown
    - During [phase 2](#phase-2) this is kept in reserve to interrupt the [Monstrosity](#amber-monstrosity-monstrosity)'s [Amber Explosion](#amber-explosion-1)
  - Use [Struggle for Controll](#struggle-for-control) when your vehicle begins casting [Amber Explosion](#amber-explosion)
  - Spam [Smash](#smash)

## Phase 1
Phase ends when Amber-Shaper gets to 70% health

This phase is just the Amber-Shaper and the [Living Amber](#living-amber) created by his [Amber Scalpel](#amber-scapel).

### Phase 1 Mechanics
- #### [Amber Scalpel](<https://www.wowhead.com/mop-classic/spell=1245000/amber-scalpel>)
  - Slow moving laser which fixates random player
  - 40 sec cooldown
  - Does 90k dps
  - Drops Molten Amber residue (residue) on ground which will disipate eventually
    - Residue do continuous damage - 40k dps - to players who touch it
    - Residue occasionally spawn [Living Amber](#living-amber).

- #### [Living Amber](<https://www.wowhead.com/mop-classic/npc=248104/living-amber>) *(Amber)*
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwow.zamimg.com%2Fuploads%2Fscreenshots%2Fnormal%2F411853-living-amber.jpg&f=1&nofb=1&ipt=27964d7ad059b84b7b855a242cb69137d7c952206c66b253d1f4f0088d0e4e3e" width=200>

  - Add spawned from pool left behind [Amber Scalpel](#amber-scalpel)
  - Fixates on a random player
  - Aura does 1.5k dps to raid
  - Explodes when it dies:
    - 70k damage to players within 8 yards
    - Healing to Amber Creatures (including [Ambers](#living-amber) and [Constructs](#mutated-construct), and possible the [Monstrosity](#amber-monstrosity-monstrosity)) 40% of max health
  - Leaves [Burning Amber](#burning-amber), when it dies.

  - Strat:
    - Target: kite the add away from melee, avoid letting it hit you.
    - Ranged: These are DPS priority. If one is targetting a healer, it becomes TOP priority.
    - Raid Lead: call out priority change "Ambers are up, ranged focus", "Amber on Heals, marked skull, range focus"

- #### [Burning Amber](<https://www.wowhead.com/mop-classic/spell=123020/burning-amber>) *(pool)*
  - a pool which does 45k dps when touching it or within 3 yards
  - Can be picked up by [Mutated Construct](#mutated-construct) for healing
  - Strat:
    - Everyone: leave these alone until phase 3
    - Everyone: Stay at least 3 yards away


- #### [Parasitic Growth](<https://www.wowhead.com/mop-classic/spell=121949/parasitic-growth>)
  - DoT, 12k dps, 30 sec
  - Damage scales with healing received
  - Strat:
    - Healers: top up character when targetted
    - Healers & Target: Shield character
    - Healers & Target: Avoid healing the target unless necessary

- #### [Reshape Life](<https://www.wowhead.com/mop-classic/spell=122370/reshape-life>)
  - Transforms a character into a [Mutated Construct](#mutated-construct)
  - In phase 1, this only happens to the tank
  - Can be healed by [Living Amber](#living-amber)'s death explosion.
  - Strat:
    - DPS: Prioritize dropping [Mutated Construct](#mutated-construct) to below 20% health immediately before swapping back to the boss.
    - Raid Lead: call out priority change: "Construct up, swap dps to construct", "Stop dps, swap back to boss"
    - If Construct catches a [Living Amber](#livin]g-amber) explosion, it needs to be dropped below 20% again. Then, follow the above strats.
    - Tanks: follow priority algorithm for [Mutated Construct](#mutated-construct) above.
    - Tanks: drop out of construct before the current active tank is transformed. You cannot tank the boss as a construct, they take additional damage from the boss.

- #### [Destroy Will](<>)
  - When the boss hits a [Construct](#mutated-construct-construct), it removes 40 willpower as well as the damage.
  - Strat: Do not be the target of the boss if you are in the vehicle.

## Phase 2
The boss gets 1 new ability, but otherwise has all the same abilities as the previous phase. Now anyone can be targetted by [Reshape Life](#reshape-life).

The boss summons the [Monstrosity](#amber-monstrosity-monstrosity). This phase continues until it is killed.

- #### [Amber Carapce](<>)
  - Boss gets a 99% damage reduction until [Monstrosity](#amber-monstrosity-monstrosity) is destroyed
  - 

- #### [Amber Monstrosity](<>) *(Monstrosity)*
  <img src="https://wow.zamimg.com/uploads/screenshots/normal/354775-amber-monstrosity.jpg" width=200> 
  
  *It looks the same as the [Construct](#mutated-construct-construct), just bigger.*

  - #### [Amber Explosion](https://www.wowhead.com/mop-classic/spell=122402/amber-explosion)
    - 225k raid damage
    - 50 sec cooldown
    - Interruptable by [Amber Strike](#amber-strike)
    - Strat:
      - Interrupting this is #1 priority


## Phase 3
This is the burn phase. It will become functionally impossible to damage a [Construct](#mutated-construct-construct) enough to [Break Free](#break-free) because of all the healing they are receiving.

When you are a construct, your HP does not matter as long as you are not the Boss's target. Your only concern is keeping your willpower up by [consuming](#consume-amber) the [pools](#burning-amber-pool), and then spamming [Smash](#smash) and [Amber Strike](#amber-strike) on cooldown.

The boss has some additional abilities. He also no longer casts [Amber Scalpel](#amber-scalpel), which means we will not get any more [pools](#burning-amber-pool)

### Phase 3 Mechancis

- #### [Concentration Mutation](<https://www.wowhead.com/mop-classic/spell=122556/concentrated-mutation>)
  - Boss now has 50% increase in attack speed and attack damage
  - Strat: Burn the boss

- #### [Volatile Amber](<https://www.wowhead.com/mop-classic/spell=123198/volatile-amber>)
  - 20% heal for [Constructs](#mutated-construct-construct)
  - Strat:
    - We are no longer trying to [Break Free](#break-free) as your health will be impossible to get down.

### Phase 3 Strategy
- Use all healing tools available when not in a [Construct](#mutated-construct-construct)
- Once in a [Construct](#mutated-construct-construct), mind your willpower and [consume](#consume-amber) the [pools](#burning-amber-pool) to bring it back up.
- Spam on the boss.