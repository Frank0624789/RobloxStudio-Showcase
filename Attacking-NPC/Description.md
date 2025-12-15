# Attacking NPC

## Overview
A small prototype of an NPC that can chase the player if the player enters within a 25 stud radius of the NPC. When the NPC is close enough, it proceeds to punch the player until the player is eliminated. 

Additionally, there is a one in three (1/3 for the demo purposes) chance on each punch that the NPC will use a "Black Flash" (inspired by Jujutsu Kaisen) that deals extra damage. After using black flash, the chances of landing another one go up to 1/70; upon the third black flash chances go down to 1/45; fourth, 1/30; fifth and beyond, 1/20.

The black flash also grants the NPC boosted max health to 120.

## What was used
  The choppy knockback system was done with BodyVelocity manipulation
  
  The blackflash system was made with a simple random number roll
  
  The punch system and player detection was done with distance/Position analysis & calculation
  
  --The NPC follows the player closest to it
