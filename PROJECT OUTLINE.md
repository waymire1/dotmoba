# dotmoba outline

## phase 0 - core sim
Deterministic 2d sim on a fixed tick. Click to move with pathing.
Click to attack, projectiles. Pixels for players, minions, towers.
Server authoritative hits with lag comp.

The bar here: two pixels last hitting a wave has to feel crisp. If
this part isn't fun then nothing after it matters, stop and fix it.

## phase 1 - items
Slot system, 4 ability (qwer) + 2 stat. First batch of ability
items: line skillshot, point and click damage, shield (self and
targeted), heal (skillshot version and click version), melee strike,
and a range conversion item. Passive framework on items. Shop, gold
from last hits plus passive income. Buying for teammates goes in
here too, not later.

## phase 2 - map
3 lanes, jungle, towers, base. Minion waves colored per lane. Need
a colorblind safe palette from the start, not patched in after.
Role colors. Jungle camps and jungle income.

## phase 3 - competitive stuff
Replays (free since the sim is deterministic). Spectator mode with
an economy overlay, since buys are basically the draft, casters
need to read them at a glance. Matchmaking. No ban phase.

## phase 4 - tuning tools
Item prices in a config we can hot load, since a patch is just a
price list. Match data: build winrates, gold curves, item timings.
Something that flags combos where the counter item comes online
later than the threat does. That's the one structural rule so it
should be automated.

## open questions
- sell back tax. this is basically our comeback mechanic since
  there are no kits, pivoting your build is the only adaptation
- can items move between slots mid game or are they locked in
- minutes 0-3 are just autos. is that actually interesting
- do stat slots get passives or raw stats only
- melee vs range pricing. range always wins lane so melee has to
  be cheaper or hit way harder, same problem as rifles vs shotguns
