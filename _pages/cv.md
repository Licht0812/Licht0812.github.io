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
  <span><i>Expected 20xx</i></span>
</div>
<div style="padding-bottom: 1em; padding-left: 1em;">
  Ph.D. in Chemical Sciences (Machine Learning and AI focus)
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 0.2em;">
  <span style="font-size: 1.15em;"><b>Your Previous University</b>, City, Country</span>
  <span><i>20xx - 20xx</i></span>
</div>
<div style="padding-bottom: 1em; padding-left: 1em;">
  B.S. in Chemistry
</div>

<hr />

## <i class="fas fa-flask"></i> Research Experience

<div style="display: flex; justify-content: space-between; margin-bottom: 0.2em;">
  <span style="font-size: 1.15em;"><b>Research Assistant</b></span>
  <span><i>20xx - Present</i></span>
</div>
<div style="padding-bottom: 1em; padding-left: 1em;">
  <i>University of Chinese Academy of Sciences</i><br>
  <ul>
    <li>Developing novel machine learning methods to solve problems in chemistry and materials science.</li>
    <li>Applying AI models to accelerate the discovery of new materials and drugs.</li>
  </ul>
</div>

<hr />

## <i class="fas fa-book"></i> Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<hr />

## <i class="fas fa-cogs"></i> Skills

* **Programming Languages:** Python, C++, etc.
* **Tools & Frameworks:** PyTorch, TensorFlow, Git, Linux
* **Languages:** Chinese (Native), English (Fluent)
