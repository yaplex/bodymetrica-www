---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

This is a test page for bodymetrica

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
