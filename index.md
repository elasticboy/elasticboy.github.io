---
layout: default
pagination:
  enabled: true
---
<div class="home">

<div class="site-header-container {% if site.cover %}has-cover{% endif %}" {% if site.cover %}style="background-image: url({{ site.cover | prepend: site.baseurl }});"{% endif %}>
  <div class="scrim {% if site.cover %}has-cover{% endif %}">
    <header class="site-header">
      <h1 class="title">{{ site.title }}</h1>
      {% if site.subtitle %}<p class="subtitle">{{ site.subtitle }}</p>{% endif %}
    </header>
  </div>
</div>

<div class="wrapper">
  <ul class="post-list">
    {% for post in paginator.posts %}
    <div>{{ post.url }}</div>
    {% endfor %}
  </ul>
</div>

</div>
