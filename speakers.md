---
layout: page
title: MATH-AI
subtitle: "The 5th Workshop on Mathematical Reasoning and AI"
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  <a target="_blank" href="https://neurips.cc/">NeurIPS 2025</a>, San Diego, December 6th or 7th (TBA), 2025
</div>

# Speakers & Panelists (Tentative)
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  {% for p in site.data.speakers %}
  {% if forloop.index<15 %}
  <div class="row">
    <div class="col-sm">
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    </div>
    <div class="col">
    {% capture id %}{{ p[1] }}{% endcapture %}
    {% include profile_detail.html p=p %}
    </div>
  </div>
  <br>
  {% endif %}
  {% endfor %}
</div>
