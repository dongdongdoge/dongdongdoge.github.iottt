---
permalink: /blog/
title: "Blog"
excerpt: "Research notes, thoughts, and updates"
author_profile: true
---

# Wentao's Blog

Welcome to my blog! Here I share insights, thoughts, and updates related to my research in secure computation, privacy-preserving technologies, and AI security.

## Recent Posts

{% for post in site.posts limit:10 %}
<div class="post-preview">
  <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  <p class="post-meta">
    <i class="far fa-calendar-alt"></i> {{ post.date | date: "%B %d, %Y" }}
    {% if post.categories %}
    <i class="fas fa-folder-open"></i> {{ post.categories | join: ", " }}
    {% endif %}
  </p>
  {% if post.excerpt %}
  <p class="post-excerpt">{{ post.excerpt }}</p>
  {% endif %}
  <div class="post-tags">
    {% for tag in post.tags %}
    <span class="tag">{{ tag }}</span>
    {% endfor %}
  </div>
</div>
<hr>
{% endfor %}

## Blog Categories

- **Research Notes** - Technical insights from my research
- **Industry Updates** - Developments in privacy and security  
- **Academic Reflections** - Thoughts on research methodology
- **Conference Reports** - Summaries from academic conferences

---

*This blog is a work in progress. I'll be adding content regularly as I continue my research journey.*

## Contact

If you have suggestions for blog topics or would like to discuss any of the content, feel free to reach out via [email](mailto:dongdongdoge@gmail.com).
