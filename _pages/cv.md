---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## <i class="fas fa-graduation-cap"></i> Education

<div style="display: flex; justify-content: space-between; margin-bottom: 0.2em;">
  <span style="font-size: 1.15em;"><b>University of Chinese Academy of Sciences</b>, Beijing, China</span>
  <span><i>2023 - Present</i></span>
</div>
<div style="padding-bottom: 1em; padding-left: 1em;">
  Ph.D. in Computer Science (Machine Learning and AI for Chemistry)
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 0.2em;">
  <span style="font-size: 1.15em;"><b>Jilin University</b>, Changchun, China</span>
  <span><i>2019 - 2023</i></span>
</div>
<div style="padding-bottom: 1em; padding-left: 1em;">
  B.S. in Measurement & Control Technology and Instrument
</div>

<hr />

{% comment %}
## <i class="fas fa-briefcase"></i> Experience

<div style="display: flex; justify-content: space-between; margin-bottom: 0px;">
  <b>Research Assistant</b>
  <i>20xx - Present</i>
</div>
<div style="padding-bottom: 15px;">
  <i style="color: #666;">University of Chinese Academy of Sciences</i><br>
  <ul>
    <li>Research topic or project responsibility description goes here.</li>
    <li>Applying AI models to accelerate the discovery in chemistry.</li>
  </ul>
</div>
{% endcomment %}

<hr />

## <i class="fas fa-book"></i> Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<hr />

{% comment %}
## <i class="fas fa-cogs"></i> Skills

* **Programming Languages:** Python, C++, etc.
* **Tools & Frameworks:** PyTorch, Git, Linux
* **Languages:** Chinese (Native), English (Fluent)
{% endcomment %}
