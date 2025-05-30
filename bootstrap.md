---
layout: bootstrap
---

## Welcome to another page

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<div class="col-lg-8 px-0">
  <p class="fs-5">You've successfully loaded up the Bootstrap starter example. It includes <a href="https://getbootstrap.com/">Bootstrap 5</a> via the <a href="https://www.jsdelivr.com/package/npm/bootstrap">jsDelivr CDN</a> and includes an additional CSS and JS file for your own code.</p>
  <p>Feel free to download or copy-and-paste any parts of this example.</p>

  <hr class="col-1 my-4">

  <a href="https://getbootstrap.com" class="btn btn-primary">Read the Bootstrap docs</a>
  <a href="https://github.com/twbs/examples" class="btn btn-secondary">View on GitHub</a>
</div>
