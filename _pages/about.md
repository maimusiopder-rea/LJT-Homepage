---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am Junteng Liu, a Ph.D. candidate in Computer Science at the [HKUST NLP Group](https://hkust-nlp.github.io/), Hong Kong University of Science and Technology, where I am advised by Prof. Junxian He. I received my B.Eng. in Automation (IEEE Honor Class) from Shanghai Jiao Tong University in June 2024.

My research focuses on natural language processing and machine learning. My current research interests include:

- LLM reasoning and reinforcement learning
- Hallucination in vision-language models (VLMs)
- LLM truthfulness and interpretability

## Education

- **Hong Kong University of Science and Technology** (2024 - Present), Ph.D. in Computer Science, HKUST NLP Group, advised by Prof. Junxian He.
- **Shanghai Jiao Tong University** (2020 - 2024), B.Eng. in Automation, IEEE Honor Class. Recipient of the Zhiyuan Honor Scholarship.

## Research Experience

- **Apple MLR**, Research Intern (2026), Cupertino, mentored by Yizhe Zhang.
- **MiniMax**, Research Intern (2025), working on large-scale logical reasoning data synthesis and training.
- **Tencent WXG**, Research Intern (2024).
- **Shanghai AI Lab**, Research Intern (2023).

## Publications

The same list is available on the [publications page](/publications/) and on [Google Scholar](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate).

{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}
