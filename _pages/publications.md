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

Publications
======
### Peer-reviewed papers
  * **Deformable CNN and Imbalance Aware Feature Learning for Singing Technique Classification**,
  Yuya Yamamoto, Juhan Nam, Hiroko Terasawa, Interspeech 2022.
    
  * **Investigating Time-Frequency Representations for Audio Feature Extraction in Singing Technique Classification**,
  Yuya Yamamoto, Juhan Nam, Hiroko Terasawa, Yuzuru Hiraga, APSIPA ASC 2021.

### Non peer-reviewed papers
  * **Analysis of Frequency, Acoustic Characteristics, and Occurrence Location of Singing Technique using Imitated J-Pop Singing Voice**,
  Yuya Yamamoto, Tomoyasu Nakano, Masataka Goto, Hiroko Terasawa, Yuzuru Hiraga, SIGMUS-132, 2021.
  
  * **A Comparison of Hand-crafted Feature and Deep-extracted Feature on Singing Technique Classification**,
  Yuya Yamamoto, Juhan Nam, Hiroko Terasawa, Yuzuru Hiraga, SIGMUS-130, 2021.
 
  * **Towards Assessment of Singing Difficulty Level of Japanese Popular Songs**,
  Yuya Yamamoto, Yuzuru Hiraga, SIGMUS-124, 2019.
  
  * **Singing Difficulty of Japanese Popular Songs: Subjective Evaluation and their Relation to Musical Features**,
  Yuya Yamamoto, Yuzuru Hiraga, JSMPC(1), 2019.