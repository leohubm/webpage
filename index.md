---
layout: default
title: Home
---

## Welcome to Eubouleus Capital
Eubouleus Capital focuses on long-term value creation through disciplined investment analysis and strategic thinking. Our approach emphasizes fundamental research, patient capital allocation, and alignment with business quality.

This site contains selected writings, research, and insights from our investment practice. We believe in the power of clear thinking, continuous learning, and the compounding effects of good decisions made consistently over time.

---

## Blog Posts
<div id="blog">
{% for post in site.posts %}
  <div class="list-item">
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <p>{{ post.description }}</p>
  </div>
{% endfor %}
</div>

---

## Projects & Research
<div id="projects">
{% for project in site.projects %}
  <div class="list-item">
    <h3><a href="{{ project.link | default: '#' }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
  </div>
{% endfor %}
</div>

---

## Contact
<div id="contact">
  <p>Email: <a href="mailto:contact@eubouleus.capital">contact@eubouleus.capital</a></p>
</div>
