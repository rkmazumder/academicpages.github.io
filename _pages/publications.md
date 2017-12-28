---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Publication
* Mazumder, R. K., Utsob, M. T. U., and Bhuiyan, A. R. (2018), Seismic Vulnerability Assessment of Medical Facilities: A GIS Based Application for Chittagong, Bangladesh, Malaysian Journal of Civil Engineering (Accepted)
* Mazumder, R. K., Uddin, S., Dey, R. and Ansary, M. A. (2016), Analytical Fragility Curves for Reinforced Concrete Building Using Single Point Scaled Spectrum Matched Ground Motion Analyses, Malaysian Journal of Civil Engineering 28(3):394-406
* Mazumder, R. K. and Ansary, M. A. (2014), Application of Capacity Spectrum Method based on ATC 40 and BNBC 1993, International Journal of Advanced Structures and Geotechnical Engineering, Vol. 03, No. 04.
* Mazumder, R. K., Khair, A.,Sakib, N., Bhuiyan, A. R. and Alam, J. (2014) Rapid Assessment Procedure for Seismic Evaluation of Existing Buildings: A Case Study for CUET Campus, Journal of South Asian Disaster Studies, Vol. 06, 2012. Click to Download
* Chowdhury, M. A. I., Mazumder, R. K., Islam, M. O. and Paul, S. (2011), Optimization of Pure Water by Reusing Domestic Water for Urban Multi-Storied Buildings, Journal of Environmental Research and Development, Vol. 6 No. 2, 295-302.
* Mazumder, R. K and Ahmed, M (2010), Vulnerability Assessment of Reinforced Concrete Frame Buildings due to Earthquake in Sylhet City, Journal of Environmental Science and Natural Resources, Vol. 3, No. 2, 81-84.

* Updating soon....
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=2_1BBHYAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
