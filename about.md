---
layout: BARE
title: About
permalink: /about/
---

Many thanks to [github][gh-url] for hosting my homepage.

# Mission:

Here I intend to document my life really; as messy as the implemenation has been I think it's time I do so.

[gh-url]: http://github.com/
[jekyll-organization]: https://github.com/jekyll

## Authors:

<ul>
  {% for author in site.authors %}
    <li>
      <h2>{{ author.name }}</h2>
      <h3>{{ author.position }}</h3>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>

## Credits:

<ul>
  {% for credit in site.Credits %}
    <li>      
      <h4><a href="{{ credit.url }}">{{ credit.title }}</a></h4>
    </li>
  {% endfor %}
</ul>