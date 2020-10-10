---

---
# Topics

a collection of things that I'm interested in.
<ul>
{% for topic in site.topics %}
    <li>
      <a href="/topics/{{ topic.url }}">{{ topic.name }}</a>
    </li>
{% endfor %}
</ul>