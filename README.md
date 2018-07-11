#

```txt
 @@@@@@   @@@  @@@   @@@@@@    @@@@@@@  @@@  @@@
@@@@@@@   @@@  @@@  @@@@@@@@  @@@@@@@@  @@@  @@@
!@@       @@!  @@@  @@!  @@@  !@@       @@!  !@@
!@!       !@!  @!@  !@!  @!@  !@!       !@!  @!!
!!@@!!    @!@!@!@!  @!@  !@!  !@!       @!@@!@!
 !!@!!!   !!!@!!!!  !@!  !!!  !!!       !!@!!!
     !:!  !!:  !!!  !!:  !!!  :!!       !!: :!!
    !:!   :!:  !:!  :!:  !:!  :!:       :!:  !:!
:::: ::   ::   :::  ::::: ::   ::: :::   ::  :::
:: : :     :   : :   : :  :    :: :: :   :   :::
```

SHOCK / A Small-Arms Tactical Skirmish System

---

## Setup and Initial Movements

## The Soldier

The primary unit of combat in *SHOCK* is a man. On most occasions you will play with anywhere from a small team to a squad or more of soldiers. At times you may see a vehicle or two. Primarily however, the system focuses on infantry type combat.

### Unit Stats

Units have three stats representing the TAP system:

- Toughness
- Awareness
- Prowess

Each stat is on a scale of 1-10, with 10 being the best.

### Troop Quality

Troops are generally rated by their overall quality and training level. This is broken down into eight different levels with *SHOCK*.

| QUALITY     | MOD | P1 | P2 | P3 | P4 |
| ----------- | --- | -- | -- | -- | -- |
| UNTRAINED   | -3  | x  |    |    |    |
| CONSCRIPT   | -2  | x  |    | x  |    |
| GREEN       | -1  | x  | x  | x  |    |
| REGULAR     | 0   | x  | x  | x  | x  |
| EXPERIENCED | 1   | xx | x  | x  | x  |
| VETERAN     | 2   | xx | x  | xx | x  |
| ELITE       | 3   | xx | xx | xx | x  |
| RAINBOW     | 4   | xx | xx | xx | xx |

Generic troops may be rated(TAP) according to their quality, with Regular being 5-5-5. Modifiers applying, an untrained generic would be 2-2-2 and a rainbow generic 9-9-9.

### Descriptions and Examples

Untrained are exactly what you would expect them to be. These are people with absolutely no prior experience or training of any manner what so ever. First time criminals, random civilians, etc.

Conscripts are those with no experience but barebones training. They have a faint idea of how things work. Gang members, Conscripted peasants, insurgents, etc.

Green troops are those with no combat experience but an acceptable basic level of training. Rookie police, fresh troops, experienced criminals, guerillas, etc.

Regular troops are those with basic training who have received some basic experience in combat. Standard Troops, police, paramilitary forces, PMCs, etc.

Experienced troops are basic troops with battle hardening, they've seen a decent handful of actions and are still standing. Also applies to standard troops with higher levels of training. Mountain warfare troops and SWAT team members.

Veteran troops are those who have all the experience needed to master their roles and/or higher levels of training. They've seen most of what combat has to offer and do not cower easily. Army Rangers and campaign hardened soldiers.

Elite troops are those equivalent with military Special Operations Forces and national Counter Terrorist Units. These are typically the highest level of the spectrum in troop quality. Green Berets, Navy Seals, GIGN, Spetsnaz, GSG-9, FBI HRT, etc.

Rainbow troops are those who are the cherry picked best of the best, from the best of the best. There is no better. Delta, DEVGRU, Tom Clancy level units, etc.

## Unit Activation

### Activation

Units are activated via chit pull.

/// Perhaps a system of activation point pooling similar to NEIS?

Max pool is equivalent to unit skill level.

### Movement

### Hold / Action

## Terrain / Cover

## Damage Systems

This section goes over the various implementations of the damage system and how they interact with each other.

### Hit Location

When a targeted unit is successfully hit, the next step is to determine where the attack hit. This is done using the table below and rolling 1d10. Cover might mitigate what would otherwise be a hit if the cover is of sufficient protection to stop the attack.

| Roll | Location    |
| ---- | ----------- |
| 01   | HEAD        |
| 02   | HEAD        |
| 03   | NECK        |
| 04   | ARM         |
| 05   | ARM         |
| 06   | UPPER TORSO |
| 07   | UPPER TORSO |
| 08   | LOWER TORSO |
| 09   | LEG         |
| 10   | LEG         |

### Damage Class

Instead of working out the exact specifics of every single gun and round known to man to create almost meaningless minute differences in stats, damage is separated by calibers into classes based on their overall raw power and penetration. These classes effect wound severity of a target if struck, as well as figuring out the effectiveness of cover and/or armor.

| Class | Mod | Type                             |
| ----- | --- | -------------------------------- |
| I     | -2  | Sub-Standard Handguns            |
| II    | -1  | Standard Handguns                |
| III   |  0  | High Power Handguns and Carbines |
| IV    |  1  | Standard Rifles                  |
| V     |  2  | Battle/Large Rifles              |
| VI    |  U  | Anti-Material and Autocannons    |

The class level also dictates the modifier on the severity chart. When making a roll for location severity, the power of the round will add or subtract from the roll to give a final result.

Class VI weapons, which would be 12.7mm/.50cal weaponry and up constitute a severity upgrade instead of a roll modifier. Whatever result you receive becomes the next tier of severity.

For example if you were to hit someone in the upper torso with a DShK 12.7mm machine gun round, and rolled a 4 on the severity, that SHOCK result becomes a DEATH result.

### Location Severity

Once the Hit Location has been determined, another 1d10 roll is made, to determine the severity of the hit, in that location, apply the damage modifier and get a final result for the target state.

| Roll | Head  | Neck  | Arms  | Upper Torso | Lower Torso | Legs  |
| ---- | ----- | ----- | ----- | ----------- | ----------- | ----- |
| 01   | STUN  | STUN  | STUN  | STUN        | STUN        | STUN  |
| 02   | WOUND | WOUND |       | WOUND       | WOUND       | WOUND |
| 03   | SHOCK |       |       |             |             |       |
| 04   | DEATH |       |       | SHOCK       |             |       |
| 05   |       |       |       |             |             |       |
| 06   |       | SHOCK | WOUND |             |             |       |
| 07   |       |       |       |             | SHOCK       |       |
| 08   |       |       |       |             |             |       |
| 09   |       | DEATH |       |             |             | SHOCK |
| 10   |       |       | SHOCK |             |             |       |

#### Details of Severity

For all intents and purposes wound severity has been relatively simplified, as the absolute realism of terminal wounding is so insanely precise and chaotic that it can be difficult to fully simulate with a computer, let alone a traditional pen and paper system.

It is for this reason that the above chart breaks lethality down into likelihoods instead of trying to work out the finer details of whether a round might hit this artery or this organ on every single shot.

##### STUN

A stun result is usually to imply or abstract a round that for some reason has little to no power/effect to provide, for example, a ricochet or grazing wound, or a round that has simply struck nothing of vital importance.

A stunned target skips his current/next turn.

##### WOUND

Bleeds are one of the main defeaters of one who has been wounded by gunshot. Wounds are simplifications of this, and scale in effect with the damage class of the round that struck them.

Every character with a wound will have to make a shock check at the end of the turn. This is simply done by making a single 1d10 roll for each character, attempting to roll higher than the total sum of wounds. Wounds are additive unless properly treated and if they amount to a total of ten or more, the unit immediately succumbs to shock.

##### SHOCK

Shock is abstracted as the various different types of shock that can befall and diminish a target, and also covers severe bleeds.

A target in shock is now incapacitated, whether conscious or not and can no longer act in accord to the battlefield. Units who are in this state must be evacuated by mission end or risk dying. Units who take more damage in this state die.

A unit who passes into shock from wounds removes the wound counters.

##### DEATH

Gunshot wounds can very easily result in death from a single shot, but very few shots actually directly and instantly kill a target. This can only be achieved by severing/destroying the spinal cord and spine to brain connecting parts above the neck. Rounds of higher power that exert enough force and pressure can destroy and rupture said areas without directly hitting them.

A target that receives death has received one of these critical shots. They instantly drop and are immediately deserviced. Otherwise this outcome is the result of lingering shock from an overly damaged or untreated target.