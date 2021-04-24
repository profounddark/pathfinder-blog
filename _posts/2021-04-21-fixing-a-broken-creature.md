---
layout: post
author: andrew
excerpt: "After having a very negative experience with a monster in an official Pathfinder 2E Adventure Path, I thought I'd take a moment to build something new that would work better while keeping things interesting."
---

A lot of my initial perspectives on Pathfinder 2E came from my first GM experience with the game: the [Extinction Curse Adventure Path](https://paizo.com/store/pathfinder/adventures/adventurePath/extinctioncurse). That's sort of funny because this Adventure Path was the second one developed for the Pathfinder 2E roleplaying game, which means it still has a fair number of development issues. Some encounters aren't balanced well, some monster design is wonky, and other strangeness make it a rather peculiar play experience, especially for a new Game Master.

## Introducing the Broken Creature

<img class="image-right" src='{{ "/assets/images/corrupted-retainer.webp" | relative_url }}' alt="The Corrupted Retainer from Paizo's The Show Must Go On">

One creature in this adventure path that gave me pause was the <creature>Corrupted Retainer</creature>, a level 2 monster that appears in the third chapter of the first module, *The Show Must Go On*. The <creature>Corrupted Retainer</creature> is a strange creature, because it feels like a case where the developer just built a player character (using the rules from the Core Rulebook) and, on realizing the numbers didn't work out, slapped some extra business on top. The resulting creature is a bit hit and miss. Mostly miss.

My initial concern with the creature is that it was built as a [Barbarian](https://2e.aonprd.com/Classes.aspx?ID=2), so it has a [Rage action](https://2e.aonprd.com/Actions.aspx?ID=3). The creature even has a rage-only ability, [No Escape](https://2e.aonprd.com/Feats.aspx?ID=137). All of this signals that this creature should rage **as soon as possible**. But, this only exacerbates what would become my major concern: the melee attack.

The <creature>Corrupted Retainer</creature> has melee attack with a +11 to hit (*high* for a creature of that level) that deals 2d8+2 piercing (*extreme*, on average, for a creature of that level). With the rage, this becomes 2d8+4 (almost extreme for a **3rd level creature**). But, more than that, it has the *fatal d10* trait, which means that on a critical success, it rolls d10s instead of d8s AND rolls an additional d10. That is to say, on a critical success, this creature deals even **MORE** damage, within the range of 12 to 58 damage.

**58 damage!!! At level 2!**

Sure, that's just the high end of the range. But, it's pretty **extreme**, especially for a level 2 monster! This is damage that one-hit-kills even the *strongest* player characters. Even without the critical success and the extra damage, there is the fact that it's average damage is also higher than the *extreme* for it's level.

Did I mention that their Armor Class was also *high* to *extreme* for their level?

After one battle with these monsters, I quickly decided that they were hot garbage and decided to do something a bit more reasonable.

## Trying Something Different

My big issue was that, as written, this creature (in essence, a basic warrior) was extremely deadly but wasn't especially interesting. On its turn, it enters a Rage and starts hitting for *too much damage*. Maybe it uses its shield, or maybe it just kills its enemies before they get a chance to attack. In my experience, a creature who's sole function is "kill PCs in one hit" isn't super fun for GMs or players, especially when that crushing damage potential isn't obvious when the battle starts. "Suprise! You've been killed!"

With that in mind, I had two goals:
* Fix the damage expression to be less outrageous; and
* Do something a bit more interesting with the Rage.

First thing first, I renamed the creature. <creature>Corrupted Retainer</creature> may have been a cool name when they started writing the module, but given that everything in the Hermitage is a *corrupted* something, I thought the name got boring quickly. Nobody wants to see "a Corrupted Retainer, a Corrupted Priest, and a Corrupted Lizard." Besides, this was supposed to be a hermitage full of people that gave up their faith in order to worship demons. With that bit of fluff in mind, I decided to call them <creature>Vile Aspirants</creature>.

What can I say, I was inspired by a thesaurus.

For the damage expression, I just grabbed the *high* damage expression for level 2 from the GameMastery Guide (1d10+4) and tweaked it to make it look more like a trident (1d8+5), as I can appreciate the idea that the same weapon should sort of look the same, no matter who uses it. That means I wanted to stick with the standard Trident d8. Of course, you may wonder why the *high* damage expression instead of **ExTReMe**?

Because I'm not a sadist.

But, also, there's still the Rage. I liked the idea that this monster started only mostly threatening but then **became** really threatening. Regarding the Rage, I had a simple idea. At first, these creatures are more defensive, using their shields to increase their AC and block damage. But, once they get hurt enough, they lose their cool and fly into a rage, ditching their shield and dealing extra the damage.

To accomplish this, I fell back on an old D&D 4E standby: **Bloodied**.

## Reacting When You're Bloodied

D&D 4E described Bloodied as:
> The bloodied value of a typical creature equals one-half its maximum hit points. A creature is bloodied when its current hit points drop to its bloodied value or lower.

On its own, Bloodied doesn't mean anything. However, certain abilities or reactions can trigger off of a creature being Bloodied. In the alternative, some abilities are only available if the creature is (or is not) Bloodied.

In my mind, "the first time the creature became Bloodied" seemed like a great opportunity to trigger the rage. At this point, it gives up on defense, ditches its shield, and goes on the full offensive. However, the change is obvious to the players, so they realize that it is important for them to defeat this enemy before it can drop the bigger damage on them.

As this was my first attempt at really messing with the Pathfinder 2E rules and system, I didn't go too crazy with this. I just mostly used the Rage ability as written, but changed it from an action to a free action that triggered on the <creature>vile aspirant</creature> first being bloodied in battle.

The net result is a creature that starts out more defensive, but shifts to a more damaging stance once the players get into it. However, this provides an interesting opportunity for the players to defeat them before they have an opportunity to put their new damage potential to good use.

<div class="pathfinder-back">
    {% include pf2-creature.html creature=site.data.creatures.vile-aspirant %}
    
</div>

## A Last Note
I included <action>Raise a Shield</action> in the stat block. This may seem unnecessary or redundant, as <action>Raise a Shield</action> is a Basic Action that anybody (with a shield) can do. However, I really like creature stat blocks to include the important stuff that a creature does. If a creature is expected to <action>Demoralize</action> or <action>Tumble Through</action> or, as in this case, <action>Raise a Shield</action> as part of its regular set of actions, it seems only appropriate to remind the GM of that.

Remind me, I mean. I'm the GM. And I forget.