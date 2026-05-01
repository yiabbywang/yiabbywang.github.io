---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral researcher at the University of Waterloo. My research focuses on land-atmosphere interactions and carbon-water coupling. My work aims to improve the understanding and estimation of water, energy, and carbon exchanges between terrestrial ecosystems and the atmosphere. Currently, I am working on peatland hydrology and carbon dynamics, with a particular interest in how peatland ecosystems respond to environmental and climate change.

I earned my M.Sc. in Earth and Environmental Sciences from the University of British Columbia, Okanagan, in 2018. My master’s research investigated the responses of forest carbon-water coupling to juvenile thinning at both the leaf and individual tree scales in a 16-year-old natural *Pinus contorta* stand. I completed my Ph.D. in Geography (Water) at the University of Waterloo in 2025. My doctoral research focused on the role of microtopography and ground cover in evapotranspiration partitioning within high-elevation wetlands in the Canadian Rocky Mountains.

---

# Selected Publications
- **Wang, Y.**, Petrone, R., & Kompanizare, M. (2024). *Toward a unified understanding of estimating evapotranspiration: The linkage between three effective parsimonious models*. <u>Water Resources Research</u>. https://doi.org/10.1029/2023WR036910

- **Wang, Y.**, Petrone, R., & Van Huizen, B. (2023). *The dependence of evaporative efficiency of vegetated surfaces on ground cover mass fractions in vegetated soils in mesic ecosystems*. <u>Hydrological Processes</u>. https://doi.org/10.1002/hyp.15036

- **Wang, Y.**, Wei, X., del Campo, A., Winkler, R., Wu, J., Li, Q., & Liu, W. (2019). *Juvenile thinning can effectively mitigate the effects of drought on tree growth and water consumption in a young Pinus contorta stand in the interior of British Columbia, Canada*. <u>Forest Ecology and Management</u>. https://doi.org/10.1016/j.foreco.2019.117667

[View all publications](/publications/)
## Papers Under Review/In Revision (Preprint Available)
{% for post in site.workingpapers reversed %}
- [{{ post.title }}]({{ post.paperurl }})  
  {{ post.venue }}, {{ post.date | date: "%Y" }}
{% endfor %}

---

# Academic Activities
{% for post in site.talks reversed limit:5 %}
- [{{ post.title }}]({{ post.url }}){% if post.venue %}, {{ post.venue }}{% endif %}{% if post.date %}, {{ post.date | date: "%Y" }}{% endif %}
{% endfor %}
[View all academic activities](/talks/)

---

# Blog Posts
{% for post in site.posts reversed limit:5 %}
- [{{ post.title }}]({{ post.url }})  
  {{ post.date | date: "%B %d, %Y" }}
{% endfor %}
[View all blog posts](/year-archive/)
