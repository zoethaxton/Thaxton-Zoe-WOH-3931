---
layout: default
title: Analysis
number: 2
---

# Analysis 1 - North Africa and the Mediterranean Theatre

Now analyze your historical subject. (1000 words). You can include images, videos and PDFs that pertain to your subject using the examples below. To add more, simply copy, paste, and change the title of your item to correspond with your media file.

# Analysis 2 - European Theatre

Start

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'PrussianInfantryHohenfriedberg'" %}
{% include media.html pages=media %}

# Analysis 3 - The Pacific Theatre

Start

{% assign media = site.media_metadata | where_exp: "item", "item.name == 'RiseOfPrussia'" %}
{% include media.html pages=media %}

# Linking to a PDF File

[Download PDF file]({{ site.baseurl }}/media_files/pdfs/newspaper1942.pdf)
