---
layout: default
---

# Let's write a story, together.

### Using GitHub, we can collaborate on writing a story together and track all the authors and changes. It's the open source way!

<div class="row">
  <div class="col-lg-7 stories">
    {% for post in site.posts %}
    {{ post.content }}<span class="story-author">Added by <a href="https://github.com/{{ post.author }}">@{{ post.author }}</a></span>
    </span>
  {% endfor %}
  </div>

  <div class="col-lg-4" style="float: right;">
    <div class="panel panel-default">
    <div class="panel-heading">
      <h4 class="panel-title">Add to the Story</h4>
    </div>
    <div class="panel-body">
      <ol>
        <li>If you don't have one already, visit <a href="http://www.github.com/signup">github.com/signup</a> and create a free account.</li>
        <li><a href="">Create a new post</a> to contribute a line to the story.</li>
        <li>For this exapmple, use this convention when naming your file: <code>YEAR-MO-DY-TITLE.md</code>. Then type out your story contribution.</li>
        <li>Click the Commit button at the bottom.</li>
        <li>This sends a pull request, asking the project owner (us!) to merge in your changes.</li>
      </ol>
      Congrats! This is the open source way!
    </div>
  </div>
</div>
