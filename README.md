# RogueTech - Blackjack weapons go to zero damage after being fired

Screencap and log files: [https://github.com/rmorrise/bt-bugrep/tree/master/rt-zero-damage]

## Description of issue

Latest mod (AIO-79-0-987-Hotfix2.exe)

The first time I fire any ballistic weapon, the stats change so that it shows the weapon's damage as "0" after it's fired. The weapon works the first time, but if I use it again in the same mission, it has no effect on subsequent turns.

If I try to fire again, the animation shows that it hit the enemy, but it does 0 damage.

Saving and restarting the game doesn't fix it. If I go back to the pre-mission autosave, it fixes it again for one shot, then it breaks.

Weapons tested:
* UAC/10 (precision ammo)
* Gauss Rifle+++ (normal ammo)
* AC/5 (normal ammo)
* AC/10 (normal ammo)

'Mechs tested:
* Blackjack
* Shadowhawk
* Urbanmech

## Reliability: 100%

## Steps to reproduce:

1) Load game from the provided save file - it should be the Blackjack's turn.
2) Attack the Commando with all weapons.
3) Play through to the Blackjack's next turn.

The Blackjack's weapons all show as having 0 damage.

I can also reproduce this when I start a new campaign, if the 'mechs in the starting lance have ballistic weapons.
