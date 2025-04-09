---
layout: post
title: Dungeons & Monsters
---

[*Dungeons & Dragons*](https://en.wikipedia.org/wiki/Dungeons_%26_Dragons) is a tabletop role-playing game that has grown in popularity in recent years. In this fantasy world, heroic adventurers face off against a wide variety of monsters.

In this post, I explore several visualizations of monsters featured in the [System Reference Document 5.1](https://www.dndbeyond.com/srd).

Each monster is described by a *stat block*, which includes a set of numerical attributes that define its characteristics—such as speed, hit points (the amount of damage it can sustain before dying), strength, size, type, dexterity, and more.

One of the most important statistics is the *Challenge Rating* (CR), which indicates how difficult a monster is for a party of player characters. The higher the CR, the tougher the monster. CR values range from 0, 1/8, 1/4, 1/2, 1, 2, and continue up to 30.

In the following visualization, each point represents a monster, grouped into "buckets" based on its CR.

<div style="display: flex; justify-content: center;">
    {% include dnd-monsters/monster_cr.html %}
</div>

We can also explore how monsters are distributed by type...

<div style="display: flex; justify-content: center;">
    {% include dnd-monsters/monster_cr_by_type.html %}
</div>

...and by size.

<div style="display: flex; justify-content: center;">
    {% include dnd-monsters/monster_cr_by_size.html %}
</div>

In addition, every monster has ability scores across six core attributes: Strength, Dexterity, Constitution, Intelligence, Wisdom, and Charisma. These can be visualized using the following radar chart.

<div style="display: flex; justify-content: center;">
    {% include dnd-monsters/monster_abilities_radar.html %}
</div>

<div class="note-box">
    The dataset and the Python scripts used to generate the visualisation are available on the associated <a href="https://github.com/ffiza/dnd-monsters" target="_blank" rel="noopener noreferrer">GitHub repository</a>.
</div>
