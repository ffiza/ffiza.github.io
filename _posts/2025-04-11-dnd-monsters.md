---
layout: post
title: Dungeons & Monsters
---

[*Dungeons & Dragons*](https://en.wikipedia.org/wiki/Dungeons_%26_Dragons) is a tabletop role-playing game that has seen a surge in popularity in recent years. In this fantasy universe, heroic adventurers confront a wide variety of monsters, each with distinct abilities and characteristics.

In this post, I explore several visualizations of monsters featured in the [System Reference Document 5.1](https://www.dndbeyond.com/srd).

Each monster is defined by a *stat block* -- a collection of numerical attributes that describe its capabilities, such as speed, hit points (the amount of damage it can endure before dying), strength, size, type, dexterity, and more.

One of the key statistics is the *Challenge Rating* (CR), which represents how difficult a monster is for a party of player characters. The higher the CR, the more formidable the monster. CR values range from 0, 1/8, 1/4, and 1/2, up through whole numbers to a maximum of 30.

In the chart below, monsters -- each represented as a dot -- are grouped into "buckets" based on their CR.

<div style="display: flex; justify-content: center; margin: 50px 0;">
    {% include dnd-monsters/monster_cr.html %}
</div>

Monsters also belong to specific types, ranging from classic undead creatures like [zombies](https://forgottenrealms.fandom.com/wiki/Zombie) and [ghouls](https://forgottenrealms.fandom.com/wiki/Ghoul) to more unusual entities like [gelatinous cubes](https://forgottenrealms.fandom.com/wiki/Gelatinous_cube), which fall under the ooze category. In total, there are fourteen types: aberration, beast, celestial, construct, dragon, elemental, fey, fiend, giant, humanoid, monstrosity, ooze, plant, and undead. This allows us to further break down CR by monster type...

<div style="display: flex; justify-content: center; margin: 50px 0;">
    {% include dnd-monsters/monster_cr_by_type.html %}
</div>

...as well as by their size.

<div style="display: flex; justify-content: center; margin: 50px 0;">
    {% include dnd-monsters/monster_cr_by_size.html %}
</div>

Each monster also has six core ability scores: Strength, Dexterity, Constitution, Intelligence, Wisdom, and Charisma. These attributes can be visualized using the following radar chart.

<div style="display: flex; justify-content: center; margin: 50px 0;">
    {% include dnd-monsters/monster_abilities_radar.html %}
</div>

Another important trait is alignment, which places monsters on two axes: lawful versus chaotic, and good versus evil. Lawful creatures follow an established code or system of rules, while chaotic ones act independently and unpredictably. Good creatures act altruistically, whereas evil ones harm others to achieve their goals. For instance, [ghouls](https://forgottenrealms.fandom.com/wiki/Ghoul) and [werewolves](https://forgottenrealms.fandom.com/wiki/Werewolf) are typically *chaotic evil*, while [unicorns](https://forgottenrealms.fandom.com/wiki/Unicorn) and [solars](https://forgottenrealms.fandom.com/wiki/Solar) (angel-like beings from the Celestial planes) are *lawful good*.

Some creatures are *unaligned*, usually because they lack moral reasoning -- like all oozes. Others can belong to any alignment, either across both axes or along a specific one. For example, a [lich](https://forgottenrealms.fandom.com/wiki/Lich) can adopt any alignment as long as it is evil.

The chart below shows the average alignment of each monster type. Most types tend toward evil, while many are neutral on the lawful/chaotic axis. Fiends and undead fall firmly on the evil end of the spectrum, directly opposing celestials, which are all good. On the lawful/chaotic axis, plants and giants lean chaotic (plants more so than giants), while celestials tend to be lawful; most other types average out as neutral.

<div style="display: flex; justify-content: center; margin: 50px 0;">
    {% include dnd-monsters/monster_avg_alignment.html %}
</div>

<div class="note-box">
    The dataset(s) and Python script(s) used to generate all the visualizations in this post are available on <a href="https://github.com/ffiza/dnd-monsters" target="_blank" rel="noopener noreferrer">GitHub</a>.
</div>