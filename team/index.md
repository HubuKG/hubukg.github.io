---
title: 团队成员
nav:
  order: 3
  tooltip: Teams
---

# <!--{% include icon.html icon="fa-solid fa-users" %}人才队伍-->


# {% include icon.html icon="fa-regular fa-user" %}负责人

{% include list.html data="members" component="portrait" filter="role == 'charge'" %}


# {% include icon.html icon="fa-regular fa-user" %}2025级

{% include list.html data="members" component="portrait" filter="role == 2025" %}

# {% include icon.html icon="fa-regular fa-user" %}2024级

{% include list.html data="members" component="portrait" filter="role == 2024" %}

# {% include icon.html icon="fa-regular fa-user" %}2023级

{% include list.html data="members" component="portrait" filter="role == 2023" %}

# {% include icon.html icon="fa-regular fa-user" %}2022级

{% include list.html data="members" component="portrait" filter="role == 2022" %}

# {% include icon.html icon="fa-regular fa-user" %}本科生
{% include list.html data="members" component="portrait" filter="role == 'undergraduate'" %}


# {% include icon.html icon="fa-regular fa-user" %}团队风采


{% capture content %}

{% include figure.html image="images/members/team_photos/jiebangguashuai.png" %}
{% include figure.html image="images/members/team_photos/bigtangbei.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
