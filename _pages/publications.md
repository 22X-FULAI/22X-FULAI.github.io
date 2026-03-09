---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
**注：本人暂无出版论文，以下所有内容为临时占位模板。**

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
