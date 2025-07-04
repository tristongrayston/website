<h2 id="projects" style="margin: 2px 0 1em;">Projects</h2>
<div class="projects">
  <ol class="project-list">
    {% assign sorted_projects = site.projects | sort: 'date' | reverse %}
    {% for project in sorted_projects %}
    <li>
      <div class="proj-row">
        <div class="col-sm-3">
          <img src="{{ project.image }}" class="teaser img-fluid z-depth-1">
        </div>
        <div class="col-sm-9" style="padding-left:20px;">
          <div class="title" style="font-weight: bold; font-size: 1.2em; margin-bottom: 8px; color: #2196F3;">{{ project.title }}</div>
          <div class="blurb">
            {{ project.content | markdownify }}
          </div>
        </div>
      </div>
    </li><br>
    {% endfor %}
  </ol>
</div>
