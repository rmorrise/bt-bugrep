# RogueTech - Blackjack weapons go to zero damage after being fired

Screencap and log files: [https://github.com/rmorrise/bt-bugrep/tree/master/rt-zero-damage]

## Description of issue

Latest mod (AIO-79-0-987-Hotfix2.exe)

Every time I fire a weapon on my Blackjack, the stats change so that it shows the weapon's damage as "0" after it's fired. I hit once with my gauss rifle +++, it blew off a Jenner's arm, then next time it showed as doing 0 damage in the status bar. Same thing with my UAC/10 (with precision ammo).

Once it got to this state, if I try to fire, the animation shows that it hit the enemy, but it plays the sound as if it missed ("no luck!") and does 0 damage.

The Blackjack has not been hit by enemy fire at all, and I don't see a status effect on it that seems relevant.
No other mechs are having this issue (they all have energy and melee weapons, though, so it could be a ballistic weapons issue?).

Saving and restarting the game doesn't fix it. If I go back to the pre-mission autosave, it fixes it again for one shot, then it breaks.

## Reliability: 100%

## Steps to reproduce:

1) Load game from the provided save file - it should be the Blackjack's turn.
2) Attack the Commando with all weapons.
3) Play through to the Blackjack's next turn.

The Blackjack's weapons all show as having 0 damage.

I can consistently reproduce this issue on any autocannon or gauss rifle, on any 'mech that I've tested so far. (Even starting a new campaign.)
