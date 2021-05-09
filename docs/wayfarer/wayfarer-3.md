---
layout: page
title: Wayfarer 3
permalink: /wayfarer/wayfarer-3/
---

Holding Page for Wayfarer 3

Details on the internals of the Wayfarer 3 can be found on the following pages:
- [LCD]({% link wayfarer/lcd.md %})
- [Keypad]({% link wayfarer/keypad.md %})
- [Printer]({% link wayfarer/printer.md %})

## Blog Posts

<div id="archives">
{% for category in site.categories %}
  <div class="archive-group">
    {% capture category_name %}{{ category | first }}{% endcapture %}
    <div id="#{{ category_name | slugize }}"></div>
    <p></p>

    <h3 class="category-head">{{ category_name }}</h3>
    <a name="{{ category_name | slugize }}"></a>
    {% for post in site.categories[category_name] %}
    <article class="archive-item">
      <h4><a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a></h4>
    </article>
    {% endfor %}
  </div>
{% endfor %}
</div>