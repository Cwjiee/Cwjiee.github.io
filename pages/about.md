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

<div class="row">
{% include about/skills.html title="Programming languages" source=site.data.programming-skills %}
{% include about/skills.html title="Technologies" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
