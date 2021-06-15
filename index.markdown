---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

{% include home_description.html %}

{% for post in site.posts %}
{% include post_excerpt.html %}
{% endfor %}
