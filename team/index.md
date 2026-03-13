---
title: 团队成员
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}人才队伍

湖北大学教育智能计算与应用团队汇聚了湖北大学计算机学院的顶尖学者和青年才俊。团队由理学博士李志飞教授为负责人，在知识图谱、推荐系统、知识追踪、智能问答等前沿领域开展深度研究。团队在国际顶级期刊和会议上持续产出高质量成果，承担多项国家重大科研项目，致力于教育智能计算与应用的创新突破。

团队秉承”日思日睿、笃志笃行”的人才理念，为每一位成员提供学术平台和广阔的发展空间，着力打造具有影响力的高水平研究团队。

# {% include icon.html icon="fa-regular fa-user" %}团队负责人

{% include list.html data="members" component="portrait" filter="role == 'charge'" %}


# {% include icon.html icon="fa-regular fa-user" %}2025级

{% include list.html data="members" component="portrait" filter="role == 2025" %}

# {% include icon.html icon="fa-regular fa-user" %}2024级

{% include list.html data="members" component="portrait" filter="role == 2024" %}

# {% include icon.html icon="fa-regular fa-user" %}2023级

{% include list.html data="members" component="portrait" filter="role == 2023" %}

# {% include icon.html icon="fa-regular fa-user" %}2022级

{% include list.html data="members" component="portrait" filter="role == 2022" %}

# {% include icon.html icon="fa-regular fa-user" %}本科生团队
{% include list.html data="members" component="portrait" filter="role == 'undergraduate'" %}


# {% include icon.html icon="fa-regular fa-user" %}团队风采


{% capture content %}

{% include figure.html image="images/members/team_photos/jiebangguashuai.png" %}
{% include figure.html image="images/members/team_photos/bigtangbei.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
