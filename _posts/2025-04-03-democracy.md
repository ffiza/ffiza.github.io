---
layout: post
title: Is the World Becoming Less Democratic?
---

Throughout history, there have been several attempts to measure the quality of democracy around the globe. The Economist Group -- a British media company and publisher of *The Economist* newspaper -- publishes its own metric, the Economist Democracy Index, which aims to describe the state of democracy in a given country on a scale from 0 to 10, with lower values associated with authoritarian regimes and higher values with well-developed democracies.

The Economist Democracy Index is constructed from sixty indicators across five categories: "electoral process and pluralism," "functioning of government," "political participation," "democratic political culture," and "civil liberties." Furthermore, countries are grouped based on their regime type:

- Full democracies: index equal to or greater than 8.00 (e.g., Norway and New Zealand)
- Flawed democracies: index between 6.00 and 7.99 (e.g., Argentina and South Korea)
- Hybrid regimes: index between 4.00 and 5.99 (e.g., Turkey and Mexico)
- Authoritarian regimes: index equal to or below 3.99 (e.g., Russia and Egypt)

As of today, the available data consists of the yearly democracy index of 167 countries, from 2006 to 2024 (except for 2007 and 2009). These countries are grouped into seven geographical regions: Asia and Australasia, Eastern Europe and Central Asia, Latin America and the Caribbean, Middle East and North Africa, Sub-Saharan Africa, North America, and Western Europe.

## The Case of Countries

The figure below shows the evolution of the democracy index for several countries: Norway (the country with the highest democracy index in 2024), Afghanistan (the country with the lowest index), Bhutan (the country with the greatest increase since 2006), Mali and Nicaragua (the two countries with the greatest decrease), and Argentina (my own country).

Norway has consistently been one of the top countries in terms of democratic development -- with scores above 9.55 since 2006 -- although it has shown a mild decline in recent years.

Since 2006, Afghanistan has been classified as an authoritarian regime. However, following the 2021 Taliban takeover of Kabul and the restoration of the Islamic Emirate of Afghanistan, there has been a dramatic suppression of democratic values in the country.

Nicaragua's sharp democratic decline has shifted its regime type from flawed democracy in 2008 to authoritarian regime in 2024. This change coincides with Daniel Ortega’s eighteen-year-long presidency and recent [reports of unfair elections](https://www.bbc.com/news/world-latin-america-59202881). Mali followed a similar trajectory, with democracy weakening after the start of the Mali War in 2012 and two *coups d'état* in 2020 and 2021.

Bhutan, on the other hand, experienced the most notable improvement in its democracy index, rising from 2.62 (authoritarian regime) in 2006 to 5.56 (hybrid regime) in 2024 (reaching a peak of 5.71 in both 2020 and 2021). Although Bhutan is governed by a parliamentary monarchy, this increase has coincided with the reign of Jigme Khesar Namgyel Wangchuck, who became king after his father’s abdication in 2006.

Finally, Argentina -- consistently categorized as a flawed democracy -- has shown a relatively stable evolution of its democracy index. It reached a peak score of 7.02 in 2015 (and again in 2018 and 2019), but has since declined to 6.51 in 2024, with a significant drop of −0.34 between 2022 and 2024.

<div align="center">
    {% include economist-democracy/time_series_by_country.html %}
</div>

## The Case for World Regions

It’s interesting to explore how democracy has evolved across the seven world regions. One useful approach is to examine the average democracy index over time for each region (see the chart below for the countries included in each group).

<div align="center">
    {% include economist-democracy/map_regions.html %}
</div>

If these regions were considered as countries, North America and Western Europe would be full democracies. Latin America and the Caribbean, Eastern Europe and Central Asia, Asia and Australasia, and Sub-Saharan Africa would be classified as hybrid regimes, while the Middle East and North Africa would be an authoritarian regime. Although all regions have lower democracy scores in 2024 than in 2006, the only change in regime type has been Latin America and the Caribbean, which shifted from a flawed democracy (between 2006 and 2020) to a hybrid regime.

Several regions show a marked decrease in their democracy index since around 2020 -- particularly North America and Latin America and the Caribbean. In the case of North America (comprising only Canada and the United States), the decline is mainly due to Canada (−0.55), while the United States saw a smaller drop (−0.07). In Latin America and the Caribbean, democratic backsliding has been especially severe in Nicaragua (−1.51), Haiti (−1.48), and El Salvador (−1.29). Only four countries in the region have improved since 2020: Dominican Republic (+0.30), Costa Rica (+0.13), Guyana (+0.10), and Uruguay (+0.06).

<div align="center">
    {% include economist-democracy/time_series_by_region.html %}
</div>

## Mapping Democracy and Its Changes

The following chart shows a map of the countries coloured by the value of the democratic index in 2024. As expected, Europe, the Americas, and Oceania contain the highest number of democratic countries.

{% include economist-democracy/map_index_2024.html %}

Looking at a map of the change in the democracy index since 2006 (see below), previously mentioned countries -- Bhutan, Nicaragua, and Mali -- stand out. Other countries with significant changes include Venezuela and Russia (more authoritarian), and Angola and Nepal (more democratic).

It is also striking that many democratic countries in 2024 have become less democratic compared to 2006, including Sweden, Iceland, Denmark, the Netherlands, Luxembourg, Australia, Germany, Canada, Austria, Spain, Czech Republic, Portugal, and Greece. Meanwhile, several nations from Sub-Saharan Africa and the Middle East and North Africa -- the two least democratic regions -- have become more democratic, such as Morocco, Angola, and Tunisia.

This leads to an important question: Have the full democracies of 2006 maintained high democratic standards in 2024? And what about the authoritarian regimes? Have any transitioned into hybrid or flawed democracies?

<div align="center">
    {% include economist-democracy/map_index_change_2006_to_2024.html %}
</div>

## Tracking Regime Changes

The chart below shows the “movement” or “migration” of countries across regime types between 2006 and 2024. The green squares represent “improvement” cases -- countries that have become more democratic -- while the red squares show “deterioration” cases -- countries that have become more authoritarian (you can hover over the boxes for a legend).

It’s expected that countries may shift to adjacent categories in the index; it’s less common for a full democracy to become an authoritarian regime -- or vice versa -- within twenty years unless triggered by major political or economic changes.

The chart shows that most regimes tend to remain the same. Of the 55 authoritarian regimes in 2006, 47 are still authoritarian in 2024. Some improvements are visible: 8 authoritarian regimes became hybrid, 5 hybrid regimes became flawed democracies, and 3 flawed democracies became full democracies.

However, there are more cases of democratic decline than improvement. Between 2006 and 2024, 12 hybrid regimes became authoritarian, 12 flawed democracies became hybrid regimes, and 4 full democracies became flawed. A particularly unfortunate case is Palestine, which was classified as a flawed democracy in 2006 but became an authoritarian regime in 2024 due to the [many conflicts](https://en.wikipedia.org/wiki/Timeline_of_the_Palestine_region#Israel_and_the_occupied_Palestinian_territories) that have affected the region in recent years.

<div align="center">
    {% include economist-democracy/regime_migration.html %}
</div>

## Takeaways

All in all, the Economist Democracy Index shows that political systems are slowly shifting toward authoritarianism. Since 2006, all regions have exhibited a move toward less democratic values, and even traditionally democratic societies like the United States and France have seen their scores decline.

Furthermore, of the 167 countries in the dataset, 29 have become more authoritarian, while only 16 have moved in a more democratic direction. While no full democracies have become authoritarian in recent years, the reverse is also true: no authoritarian regimes have become democratic.

As with any metric that attempts to describe the political, economic, or historical state of nations, these numbers should be interpreted with care. It is impossible to capture the complex inner workings of a society with a single number, and a much deeper analysis -- beyond the scope of a blog post -- would be necessary. For instance, given the widespread drop in scores after 2020, it would be interesting to explore the impact of the COVID-19 pandemic on democratic governance.

As mentioned earlier, the Economist Group is not the only institution measuring democratic quality. Other metrics include the V-Dem Democracy Indices and the Bertelsmann Transformation Index. Additional indices -- such as the Democracy Perception Index, the Fragile States Index, or the effective number of parties -- assess specific aspects of democracy.

While this post provides a broad and simplified overview of democracy’s trajectory using the Economist Democracy Index, it ultimately leads to a deeper question: Can the global decline be reversed, or are we witnessing a long-term shift toward authoritarianism?

<div class="divider"></div>

<div class="note-box">
    The analysis in this blog post is entirely independent of The Economist Group, except for utilizing publicly available data from <a href="https://en.wikipedia.org/wiki/The_Economist_Democracy_Index" target="_blank" rel="noopener noreferrer">Wikipedia</a>. Both the datasets and the Python scripts used to generate the figures are available in the associated <a href="https://github.com/ffiza/economist-democracy-index" target="_blank" rel="noopener noreferrer">GitHub repository</a>. Geographical data was obtained from <a href="https://www.naturalearthdata.com/downloads/110m-cultural-vectors/110m-admin-0-boundary-lines/" target="_blank" rel="noopener noreferrer">Natural Earth</a>.
</div>
