---
layout: page
title: About me 
cover: false
---

Hi, I am Yilun Xu. I am a first year PhD student in MIT, advised by [Tommi Jaakkola](https://people.csail.mit.edu/tommi/tommi.html). I just obtained my Bacheor’s degree from Turing Class in EECS dept, Peking University. I had the privilege of working with [Yizhou Wang](http://cfcs.pku.edu.cn/faculty/adjunct/wangyizhou/index.htm) and [Yuqing Kong](https://cfcs.pku.edu.cn/yuqkong/) in PKU, and [Stefano Ermon](https://cs.stanford.edu/~ermon/) in Stanford.
 
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



# Experience

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/mit.png" alt="" width="300" height="300">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Sept. 2020 - : Massachusetts Institute of Technology, Boston</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PhD student</p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: Tommi Jaakkola</p>
  </div>
</div>

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/pku.png" alt="" width="100" height="100">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Sept. 2016 - July. 2020: Peking University, Beijing</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;B.S. in Turing Class, Computer Science (summa cum laude)</p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: Yizhou Wang</p>
  </div>
</div>

<div style="clear: both;">
  <div style="float: left; margin-right 1em;">
    <img src="/assets/img/stanford.png" alt="" width="100" height="100">
  </div>
  <div>
    <h3>&nbsp;&nbsp;&nbsp;Jun. 2019 - Sept. 2019: Stanford University, Palo Alto</h3>
    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Visiting student</p>
    <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Advisor: Stefano Ermon</p>
  </div>
</div>
<br/>

# Miscellaneous

I am a national second-class table tennis player in China XD.

I have been playing PUBG (mobile), LoL a lot. Find me out! 

# Service 

Reviewer: NeurIPS 2020, ICLR 2021, ICML 2021