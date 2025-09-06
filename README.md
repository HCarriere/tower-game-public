# TowerGame
## About

- Waves are triggered automatically, but you can trigger them early (with cooldown)
- Killing mobs give GOLD
- Waves inscreases in difficulty very slowly
- buildings require GOLD + other resources
- resources are mined over time (everything but GOLD)


## Steps

### vectical slice 1

- [x] angular project
- [x] sprites
- [x] build simple tower
- [x] simple UI
- [x] add troops
- [x] simple spell
- [x] dark layer
- [x] simple building (spell)
- [x] gold + resources
- [x] resources nodes in the ground
- [x] remove buildings
- [x] animate some buildings
- [x] enemy attack, tower life
- [x] optimise engine (latency on firefox when buildings)
- [x] enemy wave system
- [x] clouds
- [x] simple mobile support
- [x] deltaTime
- [x] things in ground (stone, upgrades)
- [ ] more buildings (extractor, smelter, energy?, tower enhancer, bones)
- [ ] spell element system
- [ ] more spells
- [ ] spell discovery: artefacts mining
- [ ] look and feel (sparks, vibrations, wiggling, etc)
- [ ] more enemies, boss
- [ ] more buildings
- [ ] draw good tower
- [ ] better UI
- [ ] bloodstains
- [ ] saves
- [ ] UI sounds
- [ ] game sounds
- [ ] music
- [ ] employees system ?
- [ ] electron test
- [ ] setup testing : try instanciating creating all content, 


### Content Backlog

- Elements:
    - physical : protected by armor
    - ghost : strong against magical beasts
    - fire : apply fire debuff : dot (cancel ice debuff)
    - ice : apply ice debuff : slowness (put out fire)
    - lightning : apply debuff : damage+ (strong if iced)
    - acid : apply debuff : % dies
    
- Spells
    - Lightning : continuous lightning on targets
    - Laser : continuous laser
    - Fireball : explosion
    - Blades : fire blades
    - Acid balls : slow but deadly
    - Ice shards

- Modifiers
    - Spread : on hit, fire 2 other projectiles from this one (add more projectile with more spread)
    - Charm : on hit, 15% chance to charm enemies
    - Lava pool : on floor hit, create a lava pool on the floor
    - Projectile slow : decrease speed
    - Projectile fast : increase speed
    - Projectile seeker : increase seeking power
    - Elemental : change element for this one (for each element)
    - Bounce: add 1 bounce to the projectile
    - Area Expander : increase spell area
    - Target inverter: seeks the furthest enemy instead of the nearest

    
- Buildings
    - Storage : base storage is limited, so increase it with storage
    - bones collector
    - tower maintenance (heal tower vs bones)
    - limits expander
    - curse repeller (need to implement cursed rock)