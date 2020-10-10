---

---

# My collections:

## Computers & Hosts

Distinct yet inseperable. I have both a collection of computers: referring to the individual hardware devices I maintian that are capable of running a linux system. And I have a collection of hosts: referring to the network and other configuration of each machine I utilize.

<h1>Tui CSS Listing</h1>

Here are some live-examples of what you can do with the 

<a href="/Credits/{{ site.Credits.TuiCss }}">tui-css</a> basic library:

<ul>
  {% for example in site.TuiExamples %}
    <li><a href="/TuiExamples/{{ example.route }}">{{ example.title }}</a></li>
  {% endfor %}
</ul>