---
title: Member
nav:
  order: 3
  tooltip: About our team
---
{% include section.html %}
# {% include icon.html icon="fa-solid fa-users" %}Principal Investigator

{% capture text %}
助理教授
(Assistant Professor)  

國立臺灣大學電機工程學系博士
(Ph.D. in Electrical Engineering, National Taiwan University)  

專長:  控制工程、非線性系統、強化學習、多代理人系統 
(Expertise: Control Engineering, Nonlinear Systems, Reinforcement Learning, Multi-Agent Systems) 

Office:農機館 314 室

Phone:+886-2- 33665355

Email: mingli@ntu.edu.tw

{% endcapture %}

{%
  include professor.html
  image="images/mingli.jpg"
  title="江明理 Ming-Li Chiang, Ph.D."
  text=text
%}


<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}​Master Students

## 碩二

{% assign names = "xxx" | split: "|" %}

{% assign emails = "@gmail.com|" | split: "|" %}
{% include image-grid.html %}

## 碩一
{% assign names = "xxx" | split: "|" %}

{% assign emails = "@gmail.com|" | split: "|" %}
{% include image-grid.html %}
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}​In-service Master Students
{% assign names = "xxx" | split: "|" %}

{% assign emails = "@gmail.com|" | split: "|" %}
{% include image-grid.html %}
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}Undergraduate Students

{% assign names = "xxx" | split: "|" %}

{% assign emails = "@gmail.com|" | split: "|" %}
{% include image-grid.html %}
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}[Alumnis](/ntou-lcl/members/Alumni)

<!-- {% capture content %}


{% endcapture %}

{% include grid.html style="square" content=content %} -->
