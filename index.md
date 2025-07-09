---
layout: page
title: MATH-AI
subtitle: "The 5th Workshop on Mathematical Reasoning and AI"
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  <!-- (West Meeting Room 118-120, Vancouver, December 14, 2025, <a href="https://neurips.cc/virtual/2025/workshop/84719" target="_blank">Website</a>) -->
  <a target="_blank" href="https://neurips.cc/">NeurIPS 2025</a>, San Diego, December 6th or 7th (TBA), 2025
</div>




<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" />



# News

* <b style='color:red;'>We're looking for reviewers, and you can use [this form](https://forms.gle/rw8iUkLxJnZh9De29) to nominate yourself. Thank you for your help!</b>
* Our workshop is accepted to NeurIPS 2025! We're currently preparing the the <a href="./cfp">Call for Paper</a>&mdash;stay tuned!

# Overview

Mathematical reasoning is a fundamental aspect of human cognition that has been studied by scholars ranging from 
philosophers to cognitive scientists and neuroscientists. Mathematical reasoning involves analyzing complex information, identifying patterns and relationships, and drawing logical conclusions from evidence. It is central to many applications in science, engineering, finance, and everyday contexts. Recent advancements in large language models (LLMs) have unlocked new opportunities at the intersection of artificial intelligence and mathematical reasoning, ranging from new methods that solve complex problems or prove theorems, to new forms of human-machine collaboration in mathematics and beyond. 

This workshop is centered on the intersection of deep learning and mathematical reasoning, with an emphasis on, but not limited to, large language models. Our guiding theme is: *To what extent can machine learning models comprehend mathematics, and what applications could arise from this capability?* To address this question, we aim to bring together diverse participants from different backgrounds, institutions, and disciplines into our workshop. Our objective is to foster a lively and constructive dialogue on areas related, but not limited, to the following:

- **Humans vs. machines**: A comparative study of human-level mathematical reasoning and current AI techniques. How do they differ, complement one another, or intersect?
- **Measuring mathematical reasoning**: How do we design benchmarks which accurately evaluate mathematical reasoning abilities, especially in an era of large language models?
- **New capabilities**: How do we move beyond our current techniques?
- **Education**: What role can deep learning models play in mathematics education, especially in contexts with limited educational resources?
- **Applications**: What applications could AI systems enable in the near- and long-term? Example domains include software verification, sciences, engineering, finance, education, and mathematics itself.


<hr>

# Speakers & Panelists (Tentative)
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.speakers %}
    {% if forloop.index<=5 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>5 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>

<hr>

# Organizers
<!-- # Organizers -->

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <!-- <br> 
  <div class="row" style="margin: -30px;"> -->
  <div class="row">
    {% for p in site.data.organizers %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

<!-- # Program Committee
<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr> -->

# Past MATH-AI Workshops

<div class="container" style="margin-bottom: 10px;"></div>
- 4th MATH-AI Workshop at NeurIPS'24: [The 4th Workshop on Mathematical Reasoning and AI](https://mathai2024.github.io/)
- 3rd MATH-AI Workshop at NeurIPS'23: [The 3rd Workshop on Mathematical Reasoning and AI](https://mathai2023.github.io/)
- 2nd MATH-AI Workshop at NeurIPS'22: [Toward Human-Level Mathematical Reasoning](https://mathai2022.github.io/)
- 1st MATH-AI Workshop at ICLR'21: [The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- MATHAI4ED Workshop at NeurIPS'21: [Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)

<div class="container" style="margin-bottom: 10px;"></div>


<hr>

Contact: <mathai.neurips2025@gmail.com>.
