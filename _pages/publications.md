---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please see all my papers on [ADS Libary](https://ui.adsabs.harvard.edu/public-libraries/Ln4PKrMJTI2KGSaYTUw6Rw) or [Google Scholar](https://scholar.google.com/citations?user=KaFqyosAAAAJ&hl=en)
* All papers: 591 citations with h-index=15 ([ADS Libary](https://ui.adsabs.harvard.edu/public-libraries/Ln4PKrMJTI2KGSaYTUw6Rw)) or 427 citations with h-index=10 ([Google Scholar](https://scholar.google.com/citations?user=KaFqyosAAAAJ&hl=en))
* First-author papers: 


#{% if site.author.googlescholar %}
#  <div class="wordwrap">You can also find my publications on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
#{% endif %}

#{% include base_path %}

#<!-- New style rendering if publication categories are defined -->
#{% if site.publication_category %}
#  {% for category in site.publication_category  %}
#    {% assign title_shown = false %}
#    {% for post in site.publications reversed %}
#      {% if post.category != category[0] %}
#        {% continue %}
#      {% endif %}
#      {% unless title_shown %}
#        <h2>{{ category[1].title }}</h2><hr />
#        {% assign title_shown = true %}
#      {% endunless %}
#      {% include archive-single.html %}
#    {% endfor %}
#  {% endfor %}
#{% else %}
#  {% for post in site.publications reversed %}
#    {% include archive-single.html %}
#  {% endfor %}
#{% endif %}



