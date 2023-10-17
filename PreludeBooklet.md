# The Prelude Variant - v1_2023-10-16
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
And 8 **Base Prelude Card**, each containing 
</details>

## General Rules and Definitions
- Each player has a **Reserve** area to store the units they will then send on claims
- Leaders have no effect, and enter play after the prelude is done, at any friendly planets or ships.
- Technologies have no effect, except during combats

<details>
	<summary>TODO</summary>
Define what a claim is, and how claim ranges work
</details>

## Process

- Players (except Saar) place their starting Space Dock in their Home System. They place their other starting units in their reserve.

### Phase 1: Prelude Cards Selection

- Player get their race-specific Prelude Card
- Reveal 3 random Political Cards
- Players draw 7 Prelude Cards, discard 3 of them face-down

### Phase 2: Production and Claims

- In secret, players produce units at their starting Space Dock, respecting its production capacity and using the resource value of their Home System. They place these units in their reserve (reserves are private). Ignore Technologies at this step
- Some Prelude Cards will add bonus units to the reserve of a player
- In secret, players assign units from their reserve to their Prelude Cards with claims, and choose which system/planets these claim target. Unassigned units are considered as assigned to their Home System.
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