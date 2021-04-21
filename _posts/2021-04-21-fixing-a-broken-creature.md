---
layout: post
author: andrew
excerpt: "I am testing making a new template for creatures."
---

<div class="pathfinder-back">
{% include pf2-creature.html 
    name="Polar Bear"
    level="5"
    traits="n, large, animal"
    perception="+12"
    senses="low-light vision, scent (imprecise) 60 feet"
    skills="Athletics +14, Stealth +10 (+14 in icy or snowy areas), Survival +10"
    str="+5" dex ="+1" con="+5" int="-4" wis="+1" cha="-1"
    ac="22" fort="+14" ref="+10" will="+10"
    hp="73"
    speed="35 feet"
    speed-other="swim 15 feet"
    melee=
    "jaws +15, 2d8+7 piercing | 
    claw +15 (agile), 2d6+7 slashing plus Grab"
    offense=
    "Sneak Attack, The polar bear's Strikes deal an additional 1d6 precision damage to flat-footed creatures. | 
    Mauler, The polar bear gains a +3 circumstance bonus to damage rolls against creatures it has grabbed."
%}
</div>