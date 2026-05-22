---
title: Team
nav:
  order: 3
  tooltip: About our team
---

**Our lab is launching in January 2026, and we’re excited to recruit postdoctoral fellows, PhD students, and visiting scholars. If you’re interested in joining us, please feel free to email your CV. We’d love to hear from you!**

# {% include icon.html icon="fa-solid fa-users" %}Team

<div class="team-pi-row">
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
</div>

<div class="team-member-grid">
{% include list.html data="members" component="portrait" filter="role == 'lab-manager'" %}
{% include list.html data="members" component="portrait" filter="name == 'Vincent Yang, PhD'" %}
{% include list.html data="members" component="portrait" filter="name == 'George Wu'" %}
{% include list.html data="members" component="portrait" filter="name == 'Meihui Feng'" %}
{% include list.html data="members" component="portrait" filter="name == 'Yuyang Deng'" %}
{% include list.html data="members" component="portrait" filter="name == 'Priyal Tyagi'" %}
</div>

<!--
{% capture content %}

{% include section.html background="images/background.jpg" dark=true %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% include grid.html style="square" content=content %}
{% endcapture %}
-->
