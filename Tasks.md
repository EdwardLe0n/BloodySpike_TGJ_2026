# Stages

## Ideation:

- Make a general doc describing the game
- Make a list of structs/classes that need to be made
  - draw.io?

## Pre-Production

- Functional game state
- Level Prototype
  - Moving player
  - working weapon
  - stabbing the ground == spikes
  - basic enemies that just walk to the player
    - also take damage

## Production

- Spike chaining
- Sword dragging == blood
- Blood balls UI
- Parry enemy projectiles == blood bullet?

## Post-production

- More vfx
- Multiplier system for high attacks in a brief time period?
- UI camera vs World camera?
- Time slow when weapon contact

# Per Group

## App/Game

> make a copy of starship, and edit from there

### Game Classes

#### Entity

Needs to have:

- position
- velocity?
- orientation
- isAlive
- isGarbage
- cosmeticRadius
- physicsRadius

#### Creature (extends Entity)

Needs to have:

- health
- 

#### Player (extends Creature)

Needs to have:

- ????
- 

#### Enemy (extends Creature)

- tookInitialHit
  - To account for the weapon being in an enemy for multiple frames

##### Enemy Types

- Longhorn
- 

#### Blood (extends Entity)

Needs to have:

- ???

#### Spikes (extends Entity)

Needs to have:

- ???
