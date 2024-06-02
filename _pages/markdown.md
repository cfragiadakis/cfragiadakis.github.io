---
permalink: /markdown/
title: "GitHub"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---


<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=cfragiadakis&" alt="cfragiadakis" /></p>

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=cfragiadakis&layout=compact)](https://github.com/anuraghazra/github-readme-stats)


## Repositories

{% if site.data.repositories.github_repositories %}
  {% for repo in site.data.repositories.github_repositories %}
    {% include repo.html repository=repo %}
  {% endfor %}
{% endif %}

