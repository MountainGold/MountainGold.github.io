---
layout: page
title: About me
cover: false
---
Hi, I am Yilun Xu. I just obtained my Bacheor’s degree from EECS dept at Peking University, where I had the privilege of working with [Yizhou Wang](http://cfcs.pku.edu.cn/faculty/adjunct/wangyizhou/index.htm), [Yuqing Kong](https://cfcs.pku.edu.cn/yuqkong/) and [Stefano Ermon](https://cs.stanford.edu/~ermon/). I will attend MIT for my PhD study this Sept.
 
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

