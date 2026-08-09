# dotmoba
hyper competitive moba


# dotmoba

A moba where you dont pick a champion. You build one during the match.

## the idea

Every player is a pixel. Your color tells everyone your role (top,
mid, bot, support, jungle) and enemy minion waves are colored by
lane. The pixel is the hitbox. No animations getting in the way of
hit registration. Think cs 1.6 hit reg but in a moba.

## items are the kit

Everyone starts with the same base: click to move, click to attack.

- 6 item slots. 4 ability slots, 2 stat slots.
- Whatever item you put in a slot becomes your ability there. Buy a
  shield item, your Q is now a shield. Buy a skillshot item, congrats
  you're a poke character now. Heal item means you're going support.
- Items can have passives.
- You can buy items for your teammates. Support in this game means
  funding builds, not picking a healer at a select screen.

Your character comes together over the course of the game. First
buy is your commitment and the enemy team can see it.

## no bans

Mirrors are legal so there's nothing to ban.

## balance

Balanced like brood war, not like modern league. We don't decide
what's allowed. We price it.

- Abilities never get nerfed. Prices move.
- Patch notes are a price list.
- If a build looks broken, there's a counter. Go find it. The
  players are the balance team.
- One rule though: the counter has to be affordable before the
  broken thing comes online. If the counter costs 12 min of gold
  and the threat hits at 8 min, that's a real problem and we fix it.
- We only touch actual mechanics if something is broken at any
  price. Should be rare.

## netcode

2d positions, tiny game state, no animation hitboxes. The pixel art
isn't a style choice, it's what pays for the netcode. Deterministic
sim, high tick, replays basically free.
