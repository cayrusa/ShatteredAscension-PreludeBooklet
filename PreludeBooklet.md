# The Prelude Variant
*V1_2023-10-16*  
***By Cyrusa and Cue***  

> Prelude is a variant for Twilight Imperium:Shattered Ascension, that aims to replace the usual first 2 rounds of territorial claims and expansions with a higher level setup process, in order to reach the midgame (roughly round 3) quicker and with interesting board configurations.

> **Disclaimer:** Since the approach of the Prelude variant is to abstractly simulate the early game to gain time, it will not fully take into account all the details and subtle interactions of a normal early game of Shattered Ascension, like timing or Leaders.

## Table of Contents

- [Components](#components)
- [General Rules and Definitions](#general-rules-and-definitions)
- [Process](#process)

-----

## Components

- A deck of 60ish **Prelude Cards**, each containing a list of **Perks** and displaying an **initiative number**.
- 18 special **Racial Prelude Cards**, one for each playable race

<p class="aligncenter">
	<img src="./Images/PreludeTestCard.jpg" height="300"/>
</p>

<details>
	<summary>TODO</summary>
And 8 **Base Prelude Card**, each containing ...
</details>

## General Rules and Definitions
- The complete process described in this variant is referred to as **the prelude** in this booklet.
- Each player has a **Quick Reaction Force** (**QRF** for short) area to store the units they will then send on claims
- **Leaders** have no effect during the prelude, and enter play after it is complete, at any friendly planets or ships.
- **Technologies** have no effect during the prelude, except during combats
- **Racial Abilies** have no effect during the prelude, except combat-related ones.
- **Retreats** are not possible during the prelude.
- Each player will have a hand of Prelude Cards, each featuring an initiative number. The **initiative** of a player is the lowest initiative number among their cards. A player is said to **have initiative** over another when their initiative is lower.

### Claims
Most Prelude Cards contain a **Claim**. Players use these to expand their territory during the prelude. For each Claim, they will choose a planet or system to target with it, and will assign units to it. There are different types of claims.

**Types of Claims**
- Planet Claim: target a single planet. Only ground units, PDS and Space Docks can be assigned to that claim.
- System Claim: target an entire system. Any units can be assigned to that claim. Ground units, PDS and Space Docks have to be assigned to a specific planet of that system.

Additionally, each Claim has an indicated range.

**Range of a Claim**
- "Range 2": the target of that claim must be 2 spaces away or less from the player's Home System. For this purpose, Supernova and Collapsed Space-Time completely block the range calculation, and flippable wormholes are treated as having both wormholes active.
- "Adjacent": the target of that claim must be adjacent to the player's Home System, or to a system/planet that is the target of one of their other claims.
- Other: some claims have more specific ranges, or none at all.

Some Claims have additional specifications as to what they can target, like requiring a specific colour of Technology Specialty to be present.

## Process

- Players (except Saar) place their starting Space Dock in their Home System. They place their other starting units in their Quick Reaction Force.

### Phase 1: Prelude Cards Selection

- Player get their race-specific Prelude Card
- Reveal 3 random Political Cards
- Players draw 7 Prelude Cards, discard 3 of them face-down

### Phase 2: Production and Claims

- In secret, players produce units at their starting Space Dock, respecting its production capacity and using the resource value of their Home System. They place these units in their Quick Reaction Force (they are private). Ignore Technologies at this step
- Some Prelude Cards will add bonus units to the Quick Reaction Force of a player
- In secret, players assign units from their Quick Reaction Force to their Prelude Cards with claims, and choose which system/planets these claim target. Unassigned units are considered as assigned to their Home System.
- Reveal all
- Resolve Space Battle between fleets that moved to the same system. Winning fleets can land their cargo on any planets in the system. Technologies do apply for combats.
- Resolve Invasion Combat between ground units on the same planets. Technologies do apply for combats.

<details>
	<summary>TODO</summary>
Domain Counters should resolve. What if two players have ground units on a planet with Domain Counters
</details>

### Phase 3: Assembly and Trade
- Conduct an Assembly. Players have as many votes as double the influence value of their Home System. Voice of the Council can be called.
- If players got Perks relative to opening Trade Agreements, now is the time.


<details>
	<summary>TODO</summary>
Who gets Speaker? Should we let the normal setup procedure decide? Should the prelude cards deal with that? Like a unique initiative number on each prelude card, and whoever has the card with the lowest number is Speaker?
</details>