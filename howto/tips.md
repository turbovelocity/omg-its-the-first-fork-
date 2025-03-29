---
layout: page
title: Tips
---

These are tips. 

When running `jekyll serve`, it will not auto rebuils on changes to 
_config.html. You need to run `jekyll serve --watch` to enable this.


Use `{{base_url}}` to link to other pages in your site when you 
need a reference to the base URL. This is useful when you are using

``` html
* [Focaccia Recipe]({{ base_url }}/html/focaccia.html)
```
