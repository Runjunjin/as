---
layout: defaults/page
permalink: index.html
narrow: true
title: Welcome to The site of Runjunjin
---

## Attention

{% include components/intro.md %}
[Here's the full information and examples]({{ site.baseurl}}{% link _pages/about.md %})

## Versions and Functions Updating

Version: 3.0.0.0.0

{% include components/version.md %} 

[The old versions blog](2022/09/20/Disputation-RJJ-beforeblog.html) 
has upated although they preserve their old themes. 

[The Posts]({{ site.baseurl }}{% link list/posts.html %}) 
has a bunch of tips about a lot of aspects involving the blog, document, circle of friends and so on.
There's the three most-recent posts below included below. 

<hr />

### Recent Posts

{% for post in site.posts limit:4 %}
{% include components/post-card.html %}
{% endfor %}




