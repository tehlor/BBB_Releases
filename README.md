# BringBackBounty releases

## Controls
| Key         | Action      |
| ----------- | ----------- |
| Escape      | Quit       |
| F1   | Reload level        |
| Left Click   | Move        |
| (Q, W, E, or R) + Left Click | Action        |
| ScrollWheel   | Zoom Control        |
| Hold Middle Mouse   | Orbit        |

## Release Log
### 2020.02.23
New:
- Ships can be designed and saved.
- Levels now hold the enemy information.
- Cleaned up some things.

### pre-alpha
Note: 
- Actions Q, W, E and R all do different things:
    - Q is a 6 count radial mine drop. Requires your ship to slow to 10% speed for 3 secs to release.
    - W is a 1 count sniper shot. Long cooldown and does 3 damage.
    - E is a 5 count spread shot. Instead of damage it permanently slows the target by 5 units.
    - R is a 7 count spread shot. Does 8 damage.

New: 
- Menu
    - First selection is your ship. The only differences as of now are speed and health.
    - Second selection is enemy ship. The only differences as of now are speed and health.
    - Third is the map. Only differences are time given. 1 being the most, 3 being the least.
- Speed Bar in game:
    - Blue indicates active speed, yellow is a temporary reduction based on time, and red is permanent damage.

### first - February 6th 2020
Note: 
- Actions Q & W are identical
- Actions E & R are identical

Fixed:
- Waypoint marker was glitching out, behavior is as intended now.
- Due to unintended behavior, the player now "dies" on impact with an enemy.
- Zoom was not smoothed, it is now as intended.
