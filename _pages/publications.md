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
<h1 class="page__title">Additional Talks</h1>
</p>



## <span style="color:rgb(0, 119, 181)"> Studying JavaScript Security Through Static Analysis </span>

* May 2021: PhD Defense. Remote.


## <span style="color:rgb(0, 119, 181)"> Statically Analyzing Malicious JavaScript in the Wild </span>

* Mar 2021: Webinar at LORIA (France). Remote.
* Dec 2020: BINSEC Webinar at CEA (France). Remote.


## <span style="color:rgb(0, 119, 181)"> HideNoSeek: Camouflaging Malicious JavaScript in Benign ASTs </span>

* May 2020: RuhrSec. Remote. &nbsp; [Recording](https://www.youtube.com/watch?v=hhyXRRdjbls)
* Mar 2019: Grande Region Security and Reliability Day (GRSRD). Nancy, France.
* Feb 2019: MADWeb. San Diego, USA.


## <span style="color:rgb(0, 119, 181)"> JaSt: Fully Syntactic Detection of Malicious (Obfuscated) JavaScript </span>

* Nov 2018: Blackhoodie. Berlin, Germany. &nbsp; [Slides](https://blackhoodie.re/assets/archive/JaSt_blackhoodie.pdf)
* Jun 2018: Malware Meeting at LORIA. Nancy, France.
* Mar 2018: Grande Region Security and Reliability Day (GRSRD). Saarbruecken, Germany.


## <span style="color:rgb(0, 119, 181)"> Automated Clustering of File Samples for the Detection of Malware Contained in Obfuscated Script-Code </span>

* Jan 2018: Lecture at Hochschule Bonn-Rhein-Sieg. Sankt Augustin, Germany.
* Sep 2017: Master Thesis Defense at TELECOM Nancy. Nancy, France.
* Sep 2017: Talk at the German Federal Office for Information Security (BSI). Bonn, Germany.
* Jul 2017: Talk at genua. Muenchen, Germany.
* Jul 2017: Talk at CISPA. Saarbruecken, Germany.
