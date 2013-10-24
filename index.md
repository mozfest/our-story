---
layout: default
---

# Tell your story

Instructions on what to do...t

{% for post in site.posts %}
  <div class="row">
    <div class="col-lg-8">
      {{ post.content }}
    </div>
    <div class="col-lg-4">
      Added by <a href="https://github.com/{{ post.author }}">@{{ post.author }}</a>
    </div>
{% endfor %}
<div class="row">
  <div class="col-12-lg">
    <a href="#" class="btn btn-primary">Add your story</a>
  </div>
</div>
