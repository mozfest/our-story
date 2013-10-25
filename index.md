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
      <h4 class="panel-title">How to Contribute</h4>
    </div>
    <div class="panel-body">
      <ol>
        <li>In a new tab, visit <a href="http://www.github.com/signup">www.github.com</a> and sign up for a free account.</li>
        <li>Click the button below to create a new post to contribute a line to the story.</li>
        <li>Give your post a filename, then write a line.</li>
        <li>Click the contribute button at the bottom.</li>
        <li>This sends a pull request, asking the project owner (us!) to merge in your changes.</li>
      </ol>
      Congrats! This is the open source way!

      <br/><br/><a href="#" class="btn btn-info">Add your story</a>
    </div>
  </div>
</div>
