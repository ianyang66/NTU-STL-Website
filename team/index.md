---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Members (成員)


{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Alumnus (過去成員)

{% include section.html %}

{% capture content %}

陳芮甯(Luana Chen)
{% include list.html data="alumnus" component="portrait" filter="role == 'pi'" %}
陳兆閔(asef18766)
{% include figure.html image="images/photo.jpg" %}
黃浩然(Angus Wong)
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
