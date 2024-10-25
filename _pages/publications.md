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

### Journals
<!--
* **COSIAN: A Dataset for computational analysis and identification of Singing Techniuques in real-world repertoires on J-POP**
<u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, EURASIP Journal on Audio, Speech, and Music Processing (In preparation)
-->
*  **Singing technique analysis with correspondence to musical score on imitative singing of popular music**,<br>
  <u>Yuya Yamamoto</u>, Tomoyasu Nakano, Masataka Goto, Hiroko Terasawa Journal of IPSJ. Vol 64, No. 10
  <span style="color: red; "> IPSJ Journal Selected Paper </span><br>
  [pdf](https://staff.aist.go.jp/m.goto/PAPER/TIPSJ202310yamamoto.pdf)

### Peer-reviewed papers
  * **Wavetable Synthesis Using CVAE for Timbre Control Based on Semantic Label**,<br>
    Tsugumasa Yutani, <u>Yuya Yamamoto</u>, Shuyo Nakatani, Hiroko Terasawa. APSIPA ASC 2024.<br>
    [abs](https://arxiv.org/abs/2410.18628)

  * **Toward Leveraging Pre-Trained Self-Supervised Frontends for Singing Voice Understanding: Case Studies on Three Tasks**,<br>
    <u>Yuya Yamamoto</u>. APSIPA ASC 2023.<br>
    [pdf](https://yamathcy.github.io/files/apsipa23.pdf)
    
  * **PrimaDNN': A Characteristics-aware DNN customization for singing technique detection**,<br>
    <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, EUSIPCO 2023.<br>
    [pdf](https://yamathcy.github.io/files/eusipco23.pdf)

  * **Human-In-The-Loop Chord Progression Generator With Generative Adversarial Network**,<br>
  Yoshiteru Matsumoto, Hiroyoshi Ito, Hiroko Terasawa, <u>Yuya Yamamoto</u>, Yuzuru Hiraga, Masaki Matsubara APSIPA ASC 2022.<br>

  * **Analysis and detection of singing techniques in repertoires of J-POP solo singers**,<br>
  <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, ISMIR 2022. <span style="color: red; "> ISMIR student author grant </span><br>
  [pdf](https://yamathcy.github.io/files/ismir22.pdf)

  * **Deformable CNN and Imbalance Aware Feature Learning for Singing Technique Classification**,<br>
  <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, Interspeech 2022.<br>
  [pdf](https://yamathcy.github.io/files/interspeech22.pdf)
    
  * **Investigating Time-Frequency Representations for Audio Feature Extraction in Singing Technique Classification**,<br>
  <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, Yuzuru Hiraga, APSIPA ASC 2021.<br>
  [pdf](https://yamathcy.github.io/files/apsipa21.pdf)

### Extended abstracts
  * **A DBN-based regularization approach for training postprocessing-free joint beat and downbeat estimator**,<br>
  Yiming Wu, <u>Yuya Yamamoto</u>, Shunya Ishikawa. ISMIR-LBD 2024. <br>


### Non peer-reviewed papers
  * **Exploring Pretrained Self-supervised Frontends for Singing Voice Identification Tasks**,<br>
  <u>Yuya Yamamoto</u> SIGMUS-137, 2023.

  * **Semantic Timbre Control of Wavetable Synthesis based on CVAE**,<br>
  Tsugumasa Yutani, <u>Yuya Yamamoto</u>, Shuyo Nakatani, Hiroko Terasawa, SIGMUS-137, 2023. <span style="color: red; ">Sound Symposium (音学シンポジウム) Student Excellence Presentation Award </span>

  * **Towards computational analysis of singing technique for music information retrieval : A progress report of building
      dataset and statistical analysis**,
  <u>Yuya Yamamoto</u>, Daichi Moriyama, Juhan Nam, Hiroko Terasawa, JPTW 2021.
    
  * **Analysis of Frequency, Acoustic Characteristics, and Occurrence Location of Singing Technique using Imitated J-Pop Singing Voice**,<br>
  <u>Yuya Yamamoto</u>, Tomoyasu Nakano, Masataka Goto, Hiroko Terasawa, Yuzuru Hiraga, SIGMUS-132, 2021. (in Japanese)
  <span style="color: red; ">Best presentation award (Best research)</span>
  <span style="color: red; ">IPSJ Yamashita SIG Research Award</span>
  
  * **A Comparison of Hand-crafted Feature and Deep-extracted Feature on Singing Technique Classification**,<br>
  <u>Yuya Yamamoto</u>, Juhan Nam, Hiroko Terasawa, Yuzuru Hiraga, SIGMUS-130, 2021. (in Japanese)
 
  * **Towards Assessment of Singing Difficulty Level of Japanese Popular Songs**,<br>
  <u>Yuya Yamamoto</u>, Yuzuru Hiraga, SIGMUS-124, 2019. (in Japanese), <span style="color: red; ">Student encouragement award </span>
  
  * **Singing Difficulty of Japanese Popular Songs: Subjective Evaluation and their Relation to Musical Features**,<br>
  <u>Yuya Yamamoto</u>, Yuzuru Hiraga, JSMPC(1), 2019. (in Japanese)

### Dissertations
  *  **A computational approach to analysis and detection of singing techniques**
  <u>Yuya Yamamoto</u>, Ph.D. Thesis,  Doctoral Programs in Informatics, Graduate School of Comprehensive Human Sciences, University of Tsukuba. 
  [PDF](https://drive.google.com/file/d/1-tg0gnVQS3-es-XlesbonDsKLR6aO4LA/view?usp=drive_link) [Slide](https://yamathcy.github.io/files/yamamoto_defense_public.pdf)