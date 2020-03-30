---
layout: archive
title: "Publications and Conference Talks"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=NuD8rUoAAAAJ">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



<style>
  .bottom-one {margin-bottom: 1cm;}
  .bottom-two {margin-bottom: 3cm;}
</style>

<p class="bottom-two">
<h1 class="page__title">Additional Peer-Reviewed Talks</h1>
</p>

{% for post in site.talks reversed %}
<p class="bottom-one">
  {% include archive-single-talk.html %}
  </p>
{% endfor %}
