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

I am currently a Member of Technical Staff at <a href="https://www.takeargmax.com/" style="text-decoration:none;color:CornflowerBlue">Argmax</a> where we're working on on-device foundation models. Previously, I also worked at <a href="https://www.groundlight.ai" style="text-decoration:none;color:CornflowerBlue">Groundlight AI </a> and <a href="https://thirdai.com" style="text-decoration:none;color:CornflowerBlue">ThirdAI</a> where I worked on a variety of machine learning and engineering problems. Prior to that, I was a student at The University of Chicago where I double-majored in Computer Science and Computational and Applied Mathematics. I was fortunate enough to be advised by Professor <a href="https://willett.psd.uchicago.edu/" style="text-decoration:none;color:CornflowerBlue">Rebecca Willet</a>.

My research interests, broadly defined, are in statistical learning theory and machine learning systems.
For the latter, I'm mostly excited about devising fast and hardware efficient algorithms for training and inferencing large language models. This involves leveraging sparsity patterns in both the data and the model. I also enjoy working on efficient algorithms for 
high dimensional vector search on dense vector embeddings using graph-based techniques. 


Publications 
------
<i class="fas fa-link" aria-hidden="true"></i> <a href="https://blaisemuhirwa.github.io/publications/">Abstracts</a>
<ul>{% for post in site.publications reversed %}
  {% include archive-single-short-publication.html %}
{% endfor %}</ul>
  
Talks and presentations
------
<i class="fas fa-link" aria-hidden="true"></i> <a href="https://blaisemuhirwa.github.io/talks/">Slides and Recordings</a>
<ul>{% for post in site.talks reversed %}
  {% include archive-single-short-talk.html %}
{% endfor %}</ul>

Research
======


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