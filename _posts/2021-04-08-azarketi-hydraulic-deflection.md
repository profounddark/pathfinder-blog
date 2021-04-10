---
layout: post
author: andrew
excerpt: "A brief write-up on new and/or alternative feats for the Azarketi Heritage. This post makes changes to the Hydraulic Deflection feat and provides a few additional feats that improve the ability."
---

## Comparable Feats

As I developed these feats, I tried to look at existing Ancestry Feats to ensure that this wasn't too powerful or, in the alternative, not powerful enough. The goal was to make something that felt like it was useful and fit well within the existing Pathfinder mechanics.

Changing the effect of **Hydraulic Deflection** seemed straightforward. There already exist several Ancestry Feats that grant the character the ability to cast an innate cantrip: **Arcane Tattoos** (CG 11), **First World Magic** (CRB 44), **Mariner's Fire** (AG 57), **Storm's Lash** (APG 26), and **Shrouded Magic** (AG 860), to name a few. A 1st level Ancestry Feat granting the character the ability to cast a cantrip as an innate spell is not unusual. Furthermore, at least two Ancestry Feats allow a character to cast *Shield* as an innate cantrip.

However, in this case, the Feat doesn't grant the character the ability to cast an innate cantrip. It gives them an ability that is the same as a cantrip. This is comparable to the Aasimar Feat **Halo** (APG 35), an Ancestry Feat that provides an ability that is similar to a cantrip, but not *quite* the same as the cantrip. Furthermore, like **Halo**, this new **Hydraulic Deflection** can be improved with other Ancestry Feats.

## New Azarketi Ancestry Feats

<div class="pathfinder-back">
{% include pf2-feat.html
    name="Hydraulic Deflection :a:"
    level="1"
    traits="abjuration, azarketi, concentrate, primal, water"
    content="Drawing moisture from the atmosphere, you create a disc of hovering water that deflects attacks. This has the effects of a primal <spell>Shield</spell> cantrip, except it loses the force trait and gains the water trait. This cantrip is heightened to a spell level equal to half your level rounded up."
%}

{% include pf2-feat.html
    name="Resilient Deflection :f:"
    level="5"
    traits="azarketi"
    prereq="Hydraulic Deflection"
    trigger="You use the <action>Shield Block</action> reaction with <action>Hydraulic Deflection</action>"
    content="When you use the <action>Shield Block</action> reaction with <action>Hydraulic Deflection</action>, you may spend a Hero Point. If you do, the hydraulic shield does not end and you do not need to wait 10 minutes before you use <action>Hydraulic Deflection</action> again."
%}

{% include pf2-feat.html
    name="Hydraulic Barrier"
    level="9"
    traits="azarketi"
    prereq="Hydraulic Deflection"
    content="Your mastery over water has allowed you to better protect yourself from attack. When you use <action>Hydraulic Deflection</action>, the circumstance bonus you gain to AC is increased to +2."
%}
</div>