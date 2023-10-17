---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I'm a year 2 diploma student studying Information Technology in Multimedia University.
I like exploring and learning new stuff. I mostly build websites, but I've also done mobile apps, games and utility scripts.
I aspire to be a full-stack developer in the future.

<br/>
<div class="column">
<!-- {% include about/skills.html title="Programming languages" source=site.data.programming-skills %}
{% include about/skills.html title="Technologies" source=site.data.other-skills %} -->
  <p>
    <h4>Programming Languages</h4>
    <div class="row w-sm-100 ml-1">
        {% for lang in site.data.programming-languages %}
        <img src="../assets/svg/{{ lang.name }}.svg" width="50" height="50" class="m-2"/>
        {% endfor %}
    </div>
  </p>
  <br/>
  <p>
    <h4>Technologies</h4>
    <div class="row w-sm-100 ml-1">
        {% for tech in site.data.technologies %}
        <img src="../assets/svg/{{ tech.name }}.svg" width="50" height="50" class="m-2"/>
        {% endfor %}
    </div>
  </p>
</div>

<div class="row">
{% include about/timeline.html %}
</div>
