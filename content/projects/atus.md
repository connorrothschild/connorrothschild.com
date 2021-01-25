---
title: I Can Guess What You're Doing Right Now
description: Using the American Time Use Survey to predict your daily activities.
date: "2020-02-23"
audience: 'The world!'
featured: false
img: atus/header.png
img_alt: "ATUS header image, includes an image of a MacBook with the application open."
techstack: 'JavaScript, Bulma, R'
github: 'https://github.com/connorrothschild/what-are-you-doing'
url: 'https://connorrothschild.github.io/what-are-you-doing/'
---

[<InlineImage :clickable=false src="projects/atus/header.png" alt="Header"></InlineImage>](https://connorrothschild.github.io/what-are-you-doing/)

# What it is

[**What Are You Doing Right Now?**](https://connorrothschild.github.io/what-are-you-doing/) is an application that leverages data from the American Time Use Survey to guess your current activities.

# Tools used

This project was built using vanilla JavaScript, and styling was done with assistance from [Bulma](https://bulma.io/). It was rather easy to build. It was one of my first JS projects and so it was mostly an attempt to learn 🙂.

Methodologically, for each demographic profile (a combination of race, age, marital status), I found the most common activities at every given time. (Technically, I grouped per hour to prevent issues with low N's). I would then display that activity to the user, given their parameters. If that didn't fit (according to the user), I would show the second most common activity, and so on!

# Project images

<InlineImage src="projects/atus/mac-1.png" alt="" width="74%"></InlineImage>
<InlineImage src="projects/atus/phone-1.png" alt="" width="22%"></InlineImage>

<InlineImage src="projects/atus/phone-2.png" alt="" width="22%"></InlineImage>
<InlineImage src="projects/atus/mac-2.png" alt="" width="74%"></InlineImage>
