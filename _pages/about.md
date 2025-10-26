---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Hello! I am Nayoung Oh, a second-year Master’s student in [KAIST AI](https://gsai.kaist.ac.kr/) at the Korea Advanced Institute of Science and Technology ([KAIST](https://www.kaist.ac.kr/en/)). I am currently working under the supervision of [Prof. Daehyung Park](https://www.daehyungpark.com/) at the [RIRO Lab](https://rirolab.kaist.ac.kr/).

My research goal is to develop efficient and controllable robot learning systems, with a particular interest in supporting underrepresented groups. Recently, I have been focusing on:

1. State space model (SSM) based efficient small vision language action models (sVLA)
2. Diffusion-SSM based imitation learning

Please feel free to contact me at: <code>nyoh (at) kaist.ac.kr</code>


Recent Publications ([See all](/publications/))
------
{% assign reversed_publications = site.data.publications %}
{% for post in reversed_publications limit:3 %}
{% include paper.html %}
{% endfor %}

<!-- Latest News ([See all](/news/))
------
{% assign news_items = site.data.news %}
<table style="border-collapse: collapse; border:none; font-size:18px;">
  {% for item in news_items limit:5 %}
    <tr>
      <td style="width:20%; border: none; vertical-align:top;">
        <b>{{ item.date }}</b>
      </td>
      <td style="width:80%; border: none; vertical-align:top;">
        {{ item.news }}
      </td>
    </tr>
  {% endfor %}
</table> -->