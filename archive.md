---
layout: page
title: Data Archives
permalink: /archive/
---

<div class="terminal-style" markdown="1">

## > BROWSING DIRECTORY: LOG_HISTORY

### System Updates
{% for post in site.categories.system-updates %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

### Alister's Psych Evaluations
{% for post in site.categories.alister-psych-eval %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

### Vigor-9's Kinetic Tests
{% for post in site.categories.vigor-9-kinetic %}
* [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

---
**Status:** Data retrieval complete. <span class="cursor"></span>

</div>
