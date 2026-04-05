---
layout: default
title: Home
---
 
Hello! I'm **shingamer**, and this is my personal blog powered by [Jekyll](https://jekyllrb.com/) and hosted for free on [GitHub Pages](https://pages.github.com/).
 
Here you'll find posts about things I'm learning, building, and thinking about.
 
---
 
## Recent Posts
 
{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** &mdash; {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
