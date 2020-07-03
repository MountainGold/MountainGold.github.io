---
layout: page
title: About me 
cover: false
---
Hi, I am Yilun Xu. I just obtained my Bacheor’s degree from Turing Class in EECS dept, Peking University. I had the privilege of working with [Yizhou Wang](http://cfcs.pku.edu.cn/faculty/adjunct/wangyizhou/index.htm) and [Yuqing Kong](https://cfcs.pku.edu.cn/yuqkong/) in PKU, and [Stefano Ermon](https://cs.stanford.edu/~ermon/) in Stanford. I will attend MIT for my PhD study this Sept.
 
My research interests are machine learning. Previously, I mainly focus on bridging information theory and machine learning.

**Contact**: ylxu@mit.edu , xuyilun@pku.edu.cn

# Publications 
(*) denotes equal contribution

<ul>
{% for paper in site.data.papers.papers %}
  {% if paper.selected %}
  <li>
  {% include paper.html paper=paper %}
  </li>
  {% endif %}
{% endfor %}
</ul>

# Miscellaneous

I am a national second-class table tennis player in China XD.

I have been playing PUBG (mobile), LoL a lot. Find me out! 



# Experience
<figure>
<IMG SRC=”/assets/img/pku.png” ALIGN=”right” />
</figure>

<figure>
  <img src="/assets/img/pku.png" alt="this is a placeholder image">
</figure>

<figure>
  <img src="/assets/img/stanford.png" alt="this is a placeholder image">
</figure>