# Anime Moveset Frieren
## Overview
The unfinished personal project PvP game I started over the summer. The intent was for a new style of PvP game where everyone had the same kit and attacks were ranged. Since attacks are ranged, there would be more reliance on movement to dodge and disabling the opponent's movement in order to create an attack opening.

The attacks and designs are inspired by the anime Frieren: Beyond Journey's End.

There are two simple abilities and one simple mechanic.

The mechanic shown is the dash. A simple application of BodyVelocity.

The first ability shown is "Zoltraak". This blast has a small hitbox (intended for one target) and a maximum range it can hit. Any point within this range, "Zoltraak" will travel to with a varying size and position depending on the target position. There are also particles put in place for different stages of the attack. This was intended to be the M1 of the PvP system.

The second ability shown is "Purple Lightning" activated by clicking the number 2 key. This attack hits in an outward triangle of sorts. A randomly generated pattern of purple parts forms "lightning" and deals damage to the enemy. The random generation applies to the length of each part, the orientation, and the parts it connects to.
## My Notes
The most complex prototype i've scripted.

This was a project I attempted to take on all by myself. Although that burden pushed my efforts down, I walked away from the experience with broadened knowledge on particles, creating/working with them, and scripting them.

Additionally, this was my first time applying similar programming patterns to our team 302 FIRST robotics team's code. This includes distance calculations for the varying length beams for "Zoltraak" as well as Trigonometric angle calculations and yaw rotation manipulation for the purple lightning. Next step for this ability would be to add the stun effect intended.

The purple lightning is NOT a model, I didn't want to find a toolbox model for it or use particles so I scripted with many random generated parts.

## What was used

Trigonometric functions to calculate viable angles of orientation for the lightning segments in order for the bigger shape of the lightning to be a "triangle"/cone. 

Vast Use of mathematical calculations including the trigonometry but also position manipulation used for both abilities.

First time using controlled particle emission rather than simply cloning an always enabled particle emitter.



