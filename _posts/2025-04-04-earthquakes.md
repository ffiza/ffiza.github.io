---
layout: post
title: Visualising Recent Earthquakes
---

I recently came across [a compelling visualisation](https://www.reddit.com/r/dataisbeautiful/comments/1jodbwe/oc_strongest_earthquakes_in_the_past_three_decades/) on Reddit that highlighted the strongest earthquakes of the past three decades. Inspired by it, I decided to create a similar visualisation focused on a different metric.

The chart below illustrates the deadliest earthquake each year since 2001. The main axes represent the year and earthquake depth (in kilometers). The diameter of each marker is proportional to the square root of the number of fatalities, while the color corresponds to the earthquake’s magnitude. Flags indicate the location of each event, and detailed information is available by hovering over the markers.

Please note that data for the [2025 Myanmar earthquake](https://en.wikipedia.org/wiki/2025_Myanmar_earthquake) is still being updated.

<div style="display: flex; justify-content: center;">
    {% include earthquakes/earthquakes.html %}
</div>

<div class="divider"></div>

<div class="note-box">
    All data used for this visualisation was sourced from <a href="https://en.wikipedia.org/wiki/Lists_of_21st-century_earthquakes#Deadliest_earthquakes_by_year" target="_blank" rel="noopener noreferrer">Wikipedia</a>. Flag images are courtesy of <a href="https://flagcdn.com/" target="_blank" rel="noopener noreferrer">flagcdn.com</a>. The full dataset and the Python scripts used to generate the visualisation are available on the associated <a href="https://github.com/ffiza/earthquakes" target="_blank" rel="noopener noreferrer">GitHub repository</a>.
</div>
