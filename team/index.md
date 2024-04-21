---
title: 团队成员
nav:
  order: 4
  tooltip: About our team
---

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}**当前成员**
{% capture content %}

{% include figure.html image="images/2.jpg" caption="<br>张银花<br><br>博士研究生" %}
{% include figure.html image="images/3.jpg" caption="<br>李嘉<br><br>硕士研究生" %}
{% include figure.html image="images/4.jpg" caption="<br>林鑫鑫<br><br>硕士研究生" %}
{% include figure.html image="images/5.jpg" caption="<br>卓诗维<br><br>硕士研究生" %}
{% include figure.html image="images/6.jpg" caption="<br>范俊淞<br><br>硕士研究生" %}
{% include figure.html image="images/7.jpg" caption="<br>吕笑寒<br><br>硕士研究生" %}
{% include figure.html image="images/8.jpg" caption="<br>刘周安<br><br>硕士研究生" %}
{% include figure.html image="images/9.jpg" caption="<br>金云馨<br><br>硕士研究生" %}
{% endcapture %}

{% include grid.html style="square" content=content %}

{% include section.html %}


{% include section.html background="images/background.jpg" dark=true %}

<div style="text-align: center;">

探索未知，创新前沿 <br>
<br>
<br>
思辨未来，科学筑梦<br>

</div>

{% include section.html %}


# {% include icon.html icon="fa-solid fa-users" %}**已毕业学生**
{% capture content %}

{% include figure.html image="images/10.jpg" caption="<br>郑倩倩<br><br>硕士研究生" %}
{% include figure.html image="images/11.jpg" caption="<br>郭泽昆<br><br>硕士研究生" %}
{% include figure.html image="images/12.jpg" caption="<br>林臣南<br><br>硕士研究生" %}
{% include figure.html image="images/13.jpg" caption="<br>章文婷<br><br>硕士研究生" %}
{% include figure.html image="images/14.jpg" caption="<br>吴奇奇<br><br>硕士研究生" %}
{% include figure.html image="images/15.jpg" caption="<br>胡玉祯<br><br>硕士研究生" %}
{% include figure.html image="images/16.jpg" caption="<br>关颖琳<br><br>硕士研究生" %}
{% include figure.html image="images/17.jpg" caption="<br>付金龙<br><br>硕士研究生" %}
{% endcapture %}



{% include grid.html style="square" content=content %}
