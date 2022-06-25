---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### Peer-reviewed papers
  * **Deformable CNN and Imbalance Aware Feature Learning for Singing Technique Classification**,
  <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, Interspeech 2022.
    
  * **Investigating Time-Frequency Representations for Audio Feature Extraction in Singing Technique Classification**,
  <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, Yuzuru Hiraga, APSIPA ASC 2021.

### Non peer-reviewed papers
  * **Towards computational analysis of singing technique for music information retrieval : A progress report of building
      dataset and statistical analysis**,
  <u>Yuya Yamamoto</u>, Daichi Moriyama, Juhan Nam, Hiroko Terasawa, JPTW 2021.
    
  * **Analysis of Frequency, Acoustic Characteristics, and Occurrence Location of Singing Technique using Imitated J-Pop Singing Voice**,
  <u>Yuya Yamamoto</u>, Tomoyasu Nakano, Masataka Goto, Hiroko Terasawa, Yuzuru Hiraga, SIGMUS-132, 2021.
  
  * **A Comparison of Hand-crafted Feature and Deep-extracted Feature on Singing Technique Classification**,
  <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, Yuzuru Hiraga, SIGMUS-130, 2021.
 
  * **Towards Assessment of Singing Difficulty Level of Japanese Popular Songs**,
  <u>Yuya Yamamoto</u>, Yuzuru Hiraga, SIGMUS-124, 2019.
  
  * **Singing Difficulty of Japanese Popular Songs: Subjective Evaluation and their Relation to Musical Features**,
  <u>Yuya Yamamoto</u>, Yuzuru Hiraga, JSMPC(1), 2019.