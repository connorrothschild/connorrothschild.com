---
title: How Many People Have Had COVID-19?
description: A novel way to visualize COVID-19 case counts.
date: "2020-11-06"
audience: 'The world!'
featured: false
img: how-many-people/header.png
img_alt: "An example screen of the 'How Many People' application"
techstack: 'D3.js, Vue.js, Bulma'
github: 'https://github.com/connorrothschild/how-many-people'
url: 'https://connorrothschild.github.io/how-many-people'
---

[<InlineImage :clickable=false src="projects/how-many-people/header.png" alt="Header"></InlineImage>](https://connorrothschild.github.io/how-many-people)

# What it is

[How Many People Have Had COVID-19?](https://connorrothschild.github.io/how-many-people) is a small web application that visualizes COVID-19 case counts in a novel way: via state populations. The application's user can see cases either in the US or globally. The goal is to capture case counts with some comparison that everyone can understand.

# Tools used

This application was built with [Vue](https://vuejs.org/). The minimal styling was thanks to [Bulma](https://bulma.io/), my framework of choice recently. The application was simpler than some others I have built (there were only [three components](https://github.com/connorrothschild/how-many-people/tree/master/src/components)). It was mostly a fun exercise to play around with SVGs and Vue, and also an exercise to better handle user interactions. The tool needed to be robust to many changes, including 1) the adding of state populations together, 2) a 'ceiling' (the case counts) that state populations could not exceed, 3) resets on toggle of US/global views. 

# Project images

<ProjectImage src="projects/how-many-people/mac-1.png" alt=""></ProjectImage>
<ProjectImage src="projects/how-many-people/mac-2.png" alt=""></ProjectImage>

<ProjectImage src="projects/how-many-people/phone-1.png" alt="" width="48%"></ProjectImage>
<ProjectImage src="projects/how-many-people/phone-2.png" alt="" width="48%"></ProjectImage>
