---
title: Welcome to my blog
---

Testing **very important information**!

> Quoted
> `for i in j: print(k)`

Done!

<ul>
  {% for author in site.informative %}
    <li>
      <h2><a href="{{ author.url | relative_url }}">{{ author.title }}</a></h2>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>