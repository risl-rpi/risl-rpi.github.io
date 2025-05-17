---
layout: page
permalink: /people/
title: People
description: 
nav: true
nav_order: 2

faculty:
  - image: img_esen.jpg
    content: about_esen.md

phd_students:
  - image: img_jainik.jpg
    content: about_esen.md
  - image: img_taha.jpg
    content: about_esen.md

ms_students:
  - image: 
    content: about_esen.md
---

## Faculty

{% include profiles.html profiles=page.faculty %}

## Ph.D. Students

{% include profiles.html profiles=page.phd_students %}

## M.S. Students

{% include profiles.html profiles=page.ms_students %}
