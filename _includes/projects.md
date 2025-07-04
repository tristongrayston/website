<h2 id="projects" style="margin:2px 0 -15px;">Projects</h2>
<div class="projects">
  <ol class="project-list">
    {% for project in site.projects reversed %}
    <li>
      <div class="proj-row">
        <div class="col-sm-3">
          <img src="{{ project.image }}" class="teaser img-fluid z-depth-1">
        </div>
        <div class="col-sm-9" style="padding-left:20px;">
          <div class="title"><a href="{{ project.url | relative_url }}">{{ project.title }}</a></div>
          <div class="blurb">
            {{ project.content | markdownify }}
          </div>
        </div>
      </div>
    </li><br>
    {% endfor %}
  </ol>
</div>
