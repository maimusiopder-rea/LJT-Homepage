---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for publication in sorted_publications %}
<article class="mb-5">
  <h3 class="mb-1"><a href="{{ publication.url | relative_url }}">{{ publication.title }}</a></h3>
  <div class="text-muted small mb-1">{{ publication.venue }} &middot; {{ publication.date | date: "%Y" }}</div>
  <p class="mb-1">{{ publication.excerpt }}</p>
  <p class="mb-0"><a href="{{ publication.paperurl }}" target="_blank" rel="noopener noreferrer">Paper</a></p>
</article>
{% endfor %}
