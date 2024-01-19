---
title: 团队成员
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}我们的团队

（团队简介）

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

<div style="text-align: center;">

探索未知，创新前沿 <br>
<br>
<br>
思辨未来，科学筑梦<br>

</div>


{% include section.html %}

## **当前成员**
{% capture content %}

{% include figure.html image="images/2.jpg" %}
{% include figure.html image="images/3.jpg" %}
{% include figure.html image="images/4.jpg" %}
{% include figure.html image="images/5.jpg" %}
{% include figure.html image="images/6.jpg" %}
{% include figure.html image="images/7.jpg" %}
{% include figure.html image="images/8.jpg" %}
{% include figure.html image="images/9.jpg" %}
{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}

## **已毕业成员**
{% capture content %}

{% include figure.html image="images/10.jpg" %}
{% include figure.html image="images/11.jpg" %}
{% include figure.html image="images/12.jpg" %}
{% include figure.html image="images/13.jpg" %}
{% include figure.html image="images/14.jpg" %}
{% include figure.html image="images/15.jpg" %}
{% include figure.html image="images/16.jpg" %}
{% include figure.html image="images/17.jpg" %}
{% endcapture %}



{% include grid.html style="square" content=content %}
