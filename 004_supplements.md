---
layout: default
title: Supplements
number: 4
---

# Supplements

# Timeline (Collin)
<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1XjYqDW1gQyWjKLDQlfV_sxgxryJiLDOPqz5GazRsTWE&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe> 

# Supplementary Websites (Zoe)

https://study.com/learn/lesson/video/us-in-world-war-2.html 

https://www.defense.gov/News/Feature-Stories/story/article/2293108/

# Supplementary Media Files (Zoe)

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'DesertWarfareAfrica'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'ThePacificWar'" %}
{% include media.html pages=media %}

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'WW2CrashCourse'" %}
{% include media.html pages=media %}
