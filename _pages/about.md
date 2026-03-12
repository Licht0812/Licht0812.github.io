---
permalink: /
title: " "
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## <i class="fas fa-user-circle"></i> About Me

Welcome to my personal homepage. I am a PhD student at University of Chinese Academy of Sciences, working on machine learning and AI for Chemical Sciences. 

## <i class="fas fa-graduation-cap"></i> Education

<div style="display: flex; justify-content: space-between; margin-bottom: 0px;">
  <b>University of Chinese Academy of Sciences</b>
  <i>Expected 20xx</i>
</div>
<div style="color: #666; padding-bottom: 15px;">
  Ph.D. in Chemical Sciences
</div>

<div style="display: flex; justify-content: space-between; margin-bottom: 0px;">
  <b>Your Previous University</b>
  <i>20xx - 20xx</i>
</div>
<div style="color: #666; padding-bottom: 15px;">
  B.S. in Chemistry
</div>

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

## <i class="fas fa-award"></i> Honors & Awards

<ul>
  <li><b>[2024]</b> National Scholarship / Excellent Student Award</li>
  <li><b>[2023]</b> Name of another significant honor or competition prize</li>
</ul>

## <i class="fas fa-book"></i> Publications

{% assign publications_by_year = site.publications | group_by_exp: "post", "post.date | date: '%Y'" %}
{% assign sorted_years = publications_by_year | sort: "name" | reverse %}

{% for year in sorted_years %}
  <h3>{{ year.name }}</h3>
  {% for post in year.items %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}



