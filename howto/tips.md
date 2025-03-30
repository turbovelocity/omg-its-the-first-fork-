---
layout: page
title: Tips
---

* When running `jekyll serve`, it will not auto rebuild on changes to 
_config.html. You need to run `jekyll serve --watch` to enable this.

* Use {% raw %}``{{base_url}}``{% endraw %} to link to other pages in your site when you need a reference to the base URL. {% raw %} For instance: ` \[Focaccia Recipe]({{ base_url }}/html/focaccia.html)`{% endraw %} 

