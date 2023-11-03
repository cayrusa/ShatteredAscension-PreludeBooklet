# The Prelude Variant
*Draft version 4*  
***By Cyrusa and Cue***  

> Prelude is a variant for Twilight Imperium:Shattered Ascension, that aims to replace the usual first 2 rounds of territorial claims and expansions with a higher level setup process, in order to reach the midgame (roughly round 3) quicker and with interesting board configurations.

> **Disclaimer:** Since the approach of the Prelude variant is to abstractly simulate the early game to gain time, it will not fully take into account all the details and subtle interactions of a normal early game of Shattered Ascension, like timings or precise opening moves.

## Table of Contents

- [Components](#components)
- [General Rules and Definitions](#general-rules-and-definitions)
	- [Claims](#claims)
	- [Leaders](#leaders)
- [Process](#process)
	- [Game Setup](#game-setup)
	- [Phase 1: Prelude Cards Selection](#phase-1-prelude-cards-selection)
	- [Phase 2: Quick Reaction Force](#phase-2-quick-reaction-force)
	- [Phase 3: Claims](#phase-3-claims)
	- [Phase 4: Finalisation](#phase-4-finalisation)
- [Changelog](#changelog)	

-----

## Components

- A deck of 60ish **Prelude Cards**, each containing a list of **Perks**.
- 18 special **Racial Prelude Cards**, one for each playable race
- 8 identical **Basic Prelude Cards**, one for each potential player, each featuring as perk: "Range 1 system claim, increase that range value by 1 for each of these technologies your race starts with: Ion Drive, XRD Transporters, Stasis Capsules. 2 Trade Goods. 1 Action Card."

<p class="aligncenter">
	<img src="./Images/PreludeTestCard.jpg" height="300"/>
</p>

## General Rules and Definitions
- The complete process described in this variant is referred to as **the prelude** in this booklet.
- Each player has a **Quick Reaction Force** (**QRF** for short) area to store the units they will then send on claims. These areas are private.
- **Technologies** have no effect during the prelude, except during combats. When a Prelude Card lets a player choose a Technology to gain, pre-requisites apply.
- **Racial Abilies** have no effect during the prelude, except combat-related ones.
- **Retreats** are not possible during the prelude.
- **Initiative** defines an ordering of the player. The Speaker has an initiative of 1, the next player (following the Rotation Cycler) has 2, etc. When there is a timing conflict between two effects or decisions, the player with lowest initiative goes first.


### Claims
Most Prelude Cards contain a **Claim**. Players use these to expand their territory during the prelude. For each Claim, they will choose a planet or system to target with it, and will assign units to it. Each Claim has a type and a range, the possibilities are listed below, as well as additional restrictions as to the target of Claims.

**Types of Claims**  

- **Planet Claim**  
Target a single planet. Only ground units, PDS and Space Docks can be assigned to that claim.
- **System Claim**  
Target an entire system. Any units can be assigned to that claim, but if ground units, PDS or a Space Dock are assigned, at least one non-Fighter ship must also be assigned.

**Range of a Claim**

- **Range *N***  
The target of that Claim must be *N* spaces away or less from the player's Home System.
- **Adjacent**  
The target of that Claim must be adjacent to the player's Home System, or to a system/planet that is the target of one of their other Claims.
- **Other**  
Some Claims have more specific ranges, or no range restriction at all.

**Additional rules regarding Claims**

- **Impassable Systems**  
Claims may not target Asteroid Fields or Supernovae.
- **Obstacles**  
When computing the range of a Claim, **Supernovae** and **Collapsed Space-Time** block the range. **Asteroid Fields/Belts** also block the range for races which do not start with the Antimass Deflectors Technology
- **Flippable Wormholes**
When computing the range of a Claim, treat flippable Wormholes as having both sides active.
- **Sovereign Space**  
Claims may not target systems adjacent to enemy Home System, unless there is a Collapsed Space-Time between the two systems.
- **No Home Systems**  
Players may not target Claims at Home Systems, even their own.
- **One Claim per System (per Player)**  
Players may not have two Claims in the same System.

> TODO: show a picture with examples of range calculation.

### Leaders
Leaders can also be assigned to Claims. They have their usual abilities, except Diplomats (see below). Fate Rolls during the Prelude happen at the end of Phase 3.

For the prelude, the abilities of Diplomats are replaced with:

**Diplomatic Immunity**  
*If a Diplomat participates in an Invasion Combat, the opponent will have to lose control of a planet at the end of Phase 3 (they move their units/Leaders from that planet to their Home System beforehand).*

**Claim Negociation**  
*After Claims are revealed, if a player has a Claim in a system containing an enemy Diplomat, they may instead change the target of that Claim to an adjacent system containing no Claims. They must respect the type of the Claim (planet/system), but ignore its other restrictions (like a specific technology specialty).*

## Process

### Game Setup
Follow the normal Shattered Ascension setup procedure.

### Phase 1: Prelude Cards Selection

1. **Agendas**. Reveal the top 3 Political Cards from the deck. They will be voted on in Phase 4
2. **Pre-set Prelude Cards**. Player get their race-specific Prelude Card, and a Basic Prelude Card
3. **Draw and select Prelude Cards**. Players draw **7** Prelude Cards, and discard **3** of them face-down

### Phase 2: Quick Reaction Force

1. **Starting Units**. Players place their starting Space Dock in their Home System. The rest of their starting units and Leaders goes to their Quick Reaction Force.
2. **Production**. In secret, players produce units at their starting Space Dock, respecting its production capacity and using the resource value of their Home System for payment. They place these units in their Quick Reaction Force.
3. **Additional Units**. If they hold Prelude Cards granting QRF units, they add them to their Quick Reaction Force.

### Phase 3: Claims

1. **Assignments**. In secret, players assign units from their Quick Reaction Force to their Prelude Cards with Claims, and choose which system/planets these Claims target. Unassigned units are considered as assigned to their Home System. Some Prelude Cards grant units, add them as assigned to the claim of that card.
2. **Claim Reveal**. All Prelude Cards, along with their target and assigned units are revealed. Units assigned to planet claims are placed on these planets, while units assigned to a system claim are placed in space for the time being
3. **PvP Space Battles**. Resolve Space Battles in each system containing ships of 2 or more players, until no two players have ships in the same system. In initiative order, each player resolves all their Space Battles with the next player in initiative order, then with the following player in initiative order, etc... If a player has multiple Space Battle with another player, they decide the order. If a player loses all their ships in a system, all the ground units, PDS and Space Docks they also assigned to that system are destroyed.
4. **Space Domain Counters**. Players resolve space Domain Counters where they have ships. They then resolve space Artifacts where they have ships. Artifact objectives are claimed instantly and provide Victory Points immediately.
5. **Ground Assignment**. In initiative order, players with ground units, PDS or Space Dock assigned to a system may assign them to specific planets of that system. These units that did not get assigned to a planet must be placed on ships in the system with adequate capacity, or be destroyed. Saar Space Docks are not assigned to planets and stay in space.
6. **PvP Invasion Combats**. Resolve Invasion Combats on each planet containing units of 2 or more players, until no two players have units on the same planet. In initiative order, each player resolves all their Invasion Combats with the next player in initiative order, then with the following player in initiative order, etc... If a player has multiple Invasion Combats with another player, they decide the order.
7. **Ground Domain Counters**. Players resolve ground Domain Counters on planets they have units on. They then resolve ground Artifacts on planets they have units on. Artifact objectives are claimed instantly and provide Victory Points immediately.
8. **Maneuver**. Each player gets to do one Maneuver. It consists in choosing a system and moving any number of their ships from adjacent systems to that system (pick-up is allowed, but not landing. Fighters can move independantly for that purpose). Each player decides their Maneuver in secret. They are then revealed and carried out simultaneously. Finally, resolve Space Battles in systems containing ships of multiple players, in the same way as the *PvP Space Battles* step. Maneuvers may not happen in a system adjacent to an enemy Home System, unless there is a Collapsed Space-Time between the two systems.
9. **Planet Cards**. Players take the planet cards of the planets they now control (refreshed).

**Combat abilities and effects**.  
Mentak's pre-combat shots, Yin's suicide run and conversion roll, Xxcha inflicting -1 to enemy combat rolls, PDS in Invasion Combat, Bombardment... All these combat abilities and effect work in all combats.

**Fighter Capacity**.  
Fighter capacity is not checked during the prelude. However, it starts being checked again as soon as the prelude is over.

> TODO: Show an example of what a completed assignment step might look like for a player.

### Phase 4: Finalisation
1. **Prelude Cards Perks**. Players receive all the Perks from their Prelude Cards, like Trade Goods, Technologies, etc...
2. **Trade**. Players with Perks relative to opening Trade Agreements can use them to open Trade Agreements between willing players. They can open Trade Agreements they are not a part of. Players do not need a Trade Agreement Perk to self-trade. After this, place the indicated number of Trade Goods on all active Trade Agreements. 
3. **Assembly**. Players with Perks to affect the agendas may use them in initiative order, then conduct an Assembly where players have as many votes as the influence value of their Home System (to a minimum of 1), plus bonus votes from the Perks of their prelude Cards. Voice of the Council may not be called. For the purpose of resolving the agendas, this assembly is considered as taking place in the first round of the game (the one that will start after the prelude is done).
4. **Victory Points**. Every player gains 2 Victory Points.
5. **Racial Upgrade**. Conduct the "Unlock Racial Upgrades" step of the Status Phase. Players can only use their Trade Goods to pay.
6. **Command Counters**. Players can redistribute the Command Counters on their race sheet.
7. **Repair**. All units are repaired.
8. **Start the game**. The prelude is over. Note that the rule saying player may not activate enemy Home Systems during the the first round of the game does not apply when using the prelude variant.

<!-- <details>
	<summary>TODO</summary>
Something important missing?
</details> -->

-----
## Changelog
### v3 -> v4
- Phase 3:
	- Added the Maneuver step to Phase 3
	- Leader Fate Rolls happen at the end of Phase 3
	- Added Artifact resolutions to step Space Domain Counter and Ground Domain Counters of step 3, with the precision that corresponding objectives are claimed immediately
- Phase 4:
	- Trade step moved to happen before Assembly step
	- Removed Speaker bidding step (wrongly left over from last set of changes)
	- Moved Prelude Cards Perks step to be the first step of Phase 4, as that's when players will clear the board of their prelude cards, so it feels natural to have it there
	- Added a repair step
	- Assembly: More details as to how the Assembly step proceeds. Votes are now HS influence (minimum 1) + bonus votes from Perks. Voice of the Council may not be called
	- Added a step "start the game", with the note that the SA rule saying players may not activate enemy HS round 1 does not apply if the prelude variant is used
- Diplomat Abilities:
	- Moved the timing of the planet loss from Diplomatic Immunity to the end of Phase 3 (was end of the prelude)
	- Players suffering the planet loss have to move their units/leaders from that planet to their Home System. If it's optional, they could leave their Leader behind to have it Fate Roll and maybe teleport to another location.
- Players may not have multiple Claims in the same System
- Fighter capacity is not checked during the prelude
- Rewrote the Range and Additional Rules parts of the Claim section

