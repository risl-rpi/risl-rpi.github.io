---
layout: page
permalink: /people/
title: People
description: Members of the lab
nav: true
nav_order: 7

faculty:
  - name: Esen Yel
    image: img_esen.jpg
    content: about_esen.md

phd_students:
  - name: Jainik Mehta
    image: img_jainik.jpg
    content: about_esen.md

  - name: M. Taha Bekar
    image: img_taha.jpg
    content: about_esen.md

ms_students:
  - name: Shriansh Chaabra
    image: 
    content: about_esen.md
---


## Faculty

{% include profiles.html profiles=page.faculty %}

## Ph.D. Students

{% include profiles.html profiles=page.phd_students %}

## M.S. Students

{% include profiles.html profiles=page.ms_students %}