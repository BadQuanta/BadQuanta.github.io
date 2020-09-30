---
layout: TuiCss
---
# Topics

a collection of things that I'm interested in.

## Listing:

{% for topic in site.topics %}
    <li>
      <a href="/topics/{{ topic.route }}">{{ topic.title }}</a>
    </li>
{% endfor %}