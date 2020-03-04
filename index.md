---
layout: default
pagination:
  enabled: true
---
<div class="home">



<div class="wrapper">
  <ul class="post-list">
    {% for post in paginator.posts %}
    <div>{{ post.url }}</div>
    {% endfor %}
  </ul>
</div>

</div>
