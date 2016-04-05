---
layout: post
title:  "Wyrmsun Development Diary #3: Temples and Healing"
date:   2016-04-05 13:30:00 +0200
categories:  blog
comments: true
tags: [dwarf, dwarven, temple, healing, heal]
---
[Jinn](http://jinndevil.tumblr.com/) has completed the dwarven temple:

![Dwarven Temple]({{ site.url }}/images/dwarven_temple.png)

The dwarven temple exemplifies important aspects of dwarven culture. It being an underground vault, for instance, is fitting with their style of construction. The temple also demonstrates the dwarven preoccupation with keeping their traditional knowledge hidden, as mystic texts are secluded in the deep vault.

I implemented the code for temple "regeneration aura". Temples will slowly heal nearby friendly organic units, making it more practical to heal your units after a pitched battle.

![Temple Healing]({{ site.url }}/screenshots/screen_temple_regeneration.png)

I intend to take advantage of the aura code developed for this feature in the future for other uses, such as a learnable ability that increases the attack of friendly units near the hero. Additionally, potions of healing are now bought in temples, rather than in stronghold-class buildings. Temples are available in the grand strategy mode as well, where they provide additional research points.