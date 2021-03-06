---
title: Mapping Missing Migrants
description: Documenting migrants who have lost their lives while seeking refuge.
date: "2019-10-22"
audience: "The world!"
featured: true
img: map-missing-migrants/thumbnail.png
img_alt: "An example screen of the 'Mapping Missing Migrants' article"
techstack: "Mapbox, R"
github: "https://github.com/connorrothschild/map-missing-migrants/"
url: "https://connorrothschild.github.io/map-missing-migrants"
---

[<InlineImage :clickable=false src="project/map-missing-migrants/header.png" alt="Header"></InlineImage>](https://connorrothschild.github.io/map-missing-migrants)

# What it is

[**Mapping Missing Migrants**](https://connorrothschild.github.io/map-missing-migrants/) is a visual storytelling piece focused on migrants and refugees who have lost their lives while traveling to another country. It was awarded the Student Bronze in the [28th Malofiej Awards](https://www.malofiejgraphics.com/general/students-have-won-awards-too/2020/08).

# Tools used

This project was an example of a low-code but high-impact story. Rather than reinventing the wheel and implementing my own scrollytelling capabilities, I used two tools from Mapbox: their [interactive storytelling template](https://www.mapbox.com/solutions/interactive-storytelling) and [Mapbox Studio](https://www.mapbox.com/mapbox-studio). In combination, I was able to write very little code but provide a highly tailored, powerful user experience for the reader.

I used Mapbox Studio to create each of the bubbles that is present on the map. As a corollary, I used Studio to define the size, fill, and location of each bubble. I created many different layers that toggled visibility on scroll.

To trigger scroll events, I used the Mapbox storytelling template. This was a simple JSON where, for each 'view', I defined three elements: the _text_, the _layer_, and the _location_.

# Project images

<InlineImage src="project/map-missing-migrants/mac-1.png" alt="Project image for 'Mapping Missing Migrants'" width="100%"></InlineImage>

<InlineImage src="project/map-missing-migrants/mac-2.png" alt="Project image for 'Mapping Missing Migrants'" width="48%"></InlineImage>
<InlineImage src="project/map-missing-migrants/mac-3.png" alt="Project image for 'Mapping Missing Migrants'" width="48%"></InlineImage>

<InlineImage src="project/map-missing-migrants/mac-4.png" alt="Project image for 'Mapping Missing Migrants'" width="48%"></InlineImage>
<InlineImage src="project/map-missing-migrants/mac-5.png" alt="Project image for 'Mapping Missing Migrants'" width="48%"></InlineImage>

<InlineImage src="project/map-missing-migrants/phone-1.png" alt="Project image for 'Mapping Missing Migrants'" width="32%"></InlineImage>
<InlineImage src="project/map-missing-migrants/phone-2.png" alt="Project image for 'Mapping Missing Migrants'" width="32%"></InlineImage>
<InlineImage src="project/map-missing-migrants/phone-3.png" alt="Project image for 'Mapping Missing Migrants'" width="32%"></InlineImage>
