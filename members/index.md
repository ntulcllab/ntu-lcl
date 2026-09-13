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

{% assign images = "images/cheyu.JPG|images/kuanyu.jpg|images/chunyu.jpg|images/kuanchen.jpg|images/yuju.jpg" | split: "|" %}
{% assign names = "周哲宇 CHE-YU CHOU|王寬裕 KUAN-YU WANG|楊竣宇 CHUN-YU YANG|鄒冠程 KUAN-CHENG TSOU|陳郁儒 YU-JU CHEN" | split: "|" %}
{% assign emails = "11453035@mail.ntou.edu.tw|11453006@email.ntou.edu.tw|11453077@email.ntou.edu.tw|zouguancheng@gmail.com|11353093@mail.ntou.edu.tw" | split: "|" %}
{% include image-grid.html %}

## 碩一
{% assign images = "images/wen.jpg|images/hsiaokang.jpg|images/S__13787228.jpg|images/S__13787224.jpg|images/huashan.jpg" | split: "|" %}
{% assign names = "溫翔宇 SIANG-YU WEN|林曉岡 LIN HSIAO KANG|林冠廷 LIN  KUAN-TING|李盛玄 Lee Sheng hsuan|趙華杉 Chao Hua Shan" | split: "|" %}
{% assign emails = "11453006@email.ntou.edu.tw|r15631046@ntu.edu.tw|r15631038@ntu.edu.tw|r14631040@ntu.edu.tw|r15631062@ntu.edu.tw" | split: "|" %}
{% include image-grid.html %}
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}​In-service Master Students
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}Undergraduate Students
<!-- section break -->
# {% include icon.html icon="fa-solid fa-users" %}[Alumnis](/ntou-lcl/members/Alumni)

<!-- {% capture content %}


{% endcapture %}

{% include grid.html style="square" content=content %} -->
