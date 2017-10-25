---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<ul>
  <li>
    <a href="{{ site.github.url }}/category/2017pool">2017 Winners</a>
  </li>
  <li>
    <a href="{{ site.github.url }}/category/2016pool">2016 Winners</a>
  </li>
<ul>

</ul>


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.github.url }}/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
