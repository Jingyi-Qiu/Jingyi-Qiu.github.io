---
layout: page
permalink: /publications/
title: Publications
excerpt_text: Publications and working papers by Jingyi Qiu (University of Michigan School of Information).
---

<p class="scholar-link">
  <a href="https://scholar.google.com/citations?user={{ site.scholar_userid }}" target="_blank" rel="noopener">View my full list of publications on <strong>Google Scholar</strong></a>
</p>

{% for group in site.data.publications %}
<section class="publication-category">
  <h4>{{ group.section }}</h4>
  <ol class="bibliography">
    {% for pub in group.items %}
      {% include publication.html pub=pub %}
    {% endfor %}
  </ol>
</section>
{% endfor %}
