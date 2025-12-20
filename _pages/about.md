---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}
Hi there! 

I am currently a Member of Technical Staff at <a href="https://www.argmaxinc.com/" style="text-decoration:none;color:CornflowerBlue">Argmax</a> where we're working on on-device foundation model inference. Previously, I also worked at <a href="https://www.groundlight.ai" style="text-decoration:none;color:CornflowerBlue">Groundlight AI </a> and <a href="https://thirdai.com" style="text-decoration:none;color:CornflowerBlue">ThirdAI</a> where I worked on a variety of machine learning and engineering problems. Prior to that, I was a student at The University of Chicago where I double-majored in Computer Science and Computational and Applied Mathematics.

Among other things, I am also the maintainer of <a href="https://www.flatnav.net/" style="text-decoration:none;color:CornflowerBlue">flatnav</a>, a robust and memory-efficient library for performing vector search at scale.

My research interests, broadly defined, are in information retrieval, learning theory and machine learning systems. On the IR side of things, I enjoy working on efficient algorithms for high-dimensional vector search on dense embeddings. On the ML systems side, I am mostly excited about ways we can make inference faster for foundation models.

Preprints and Publications 
------
<i class="fas fa-link" aria-hidden="true"></i> <a href="https://blaisemuhirwa.github.io/publications/" style="text-decoration:none;color:CornflowerBlue">Abstracts</a>
<ul>{% for post in site.publications reversed %}
  {% include archive-single-short-publication.html %}
{% endfor %}</ul>
  
Talks and presentations
------
<i class="fas fa-link" aria-hidden="true"></i> <a href="https://blaisemuhirwa.github.io/talks/" style="text-decoration:none;color:CornflowerBlue">Slides and Recordings</a>
<ul>{% for post in site.talks reversed %}
  {% include archive-single-short-talk.html %}
{% endfor %}</ul>

<!-- Research
====== -->


<!-- - <a href="https://arxiv.org/pdf/2412.01940" style="text-decoration:none; color:CornflowerBlue">
Down with the Hierarchy: The ‘H’ in HNSW Stands for “Hubs”</a>
*arXiv preprint. Blaise Munyampirwa, Vihan Lakshman, Benjamin Coleman, 2024.*

- <a href="https://app.virtualpostersession.org/e/efba16cd3274f1b2dbd5570e9fe9a30d" style="text-decoration:none; color:CornflowerBlue"> 
Machine Learning for Usage Based Insurance</a>
*Poster Presentation. Blaise Munyampirwa, Rebecca Willett and Willem Marais, 2022.*

- <a href="https://www.redjournal.org/article/S0360-3016(19)34202-6/fulltext" style="text-decoration:none; color:CornflowerBlue">Deep Learning Detects Actionable Molecular and Clinical Features Directly from Head/Neck Squamous Cell Carcinoma Histopathology Slides</a>
*International Journal of Radiation Oncology*, 2020


Talks and Presentations
======

- <a href="https://blaisemuhirwa.github.io/_files/talks/flatnav-talk.pdf" style="text-decoration:none; color:CornflowerBlue">
Optimizing HNSW in the Age of Vector Databases</a>
*Presented at Amazon Search, Palo Alto CA.* -->