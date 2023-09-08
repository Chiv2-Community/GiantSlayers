
## Features
- Killing a player increases Size and Heals the victor
- _(WIP)_ Additional Abilities available with increased size
- Timing and bonus strength configurable per server
- Animation speed is reduced for giants.

### Levels
Rounded (floor) Scale is used as Level

- Level-up is indicated ingame. Max. level is 8
![[Pasted image 20230908115150.png]]

#### Current Level Bonuses
##### Level 2 - Stallion Strength
- You Kick ability does more damage and knocks players back. Less effective to other giants
- Narrow Cone AoE
##### Level 5 - Impactful Presence
You're officially a Giant.

- Landing a jump (shatters the ground below) causes an explosive impact, 
setting nearby players ablaze and knocking them up in the air.
- Less effective against other Giants


### What exactly affects the Scale?
#### Kill Bonus
- Killer is healed by 50 + additional 50 over time
- Size bonus gained is based on:
    - Killer's scale (12.5%)
    - Victim's scale (25%)
#### (WIP) Inactivity
After 15 seconds of inactivity (Hasn’t killed a player) scale is lowered gradually

- Killing someone interrupts the process
- Scale is reduced to $\frac{S}{3}$
### Configuration
Most factors and timers can be changed via config (Engine.ini):
```ini
[TODO]
```
## Wishlist/TODO
- Scale Carryables with the characters size
- Giant’s attacks with blunt weapons should either instagib or ragdoll players on kill.
- Global announcement when someone reaches max level
- Ground shake when a giant is running
- (WIP) Some fitting sound effects (growing, shrinking)
- Max HP increase?