---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
* **Accepted**
  * Chen, Y., **An, B.**, Ma, Y., & Fu, Z. (2023). Analysis of pneumoconiosis cases and characteristics from 2004–2019 in Shandong Province. Am J Biomed Sci & Res, 2023 20 (1) AJBSR.MS.ID.002668. DOI: 10.34297/AJBSR.2023.20.002668

* **Under Review**
  * **An, B.**, Wang, X., & Chow, K. Three years of COVID in Hong Kong - the Drivers of the Policy, Science, Resources, Economics or Political Will.
  * Yarime, M., Li, H., **An, B.**, Zuo, R., Li, Z., Li, Z., & Chen, Z. AI for Sustainability in China: Responsible AI Technology in Practice for Better Environmental Sustainability. Global Partnership on Artificial Intelligence.
  * **An, B.** Opportunities and Challenges to Implement Circular Economy in the GBA: An Analysis on Electric Vehicle Battery Recycling. Science and Public Policy.

* **In Progress**
  * **An, B.** Opportunities and Challenges of Sustainable Agricultural Technology Development: A Case of Agricultural Technology in Saline Alkali Land.
  * Wang, H., **An, B.** Non-only Children and Their Cognition: Evidence from China.
  * Chen, Y., **An, B.** Characteristics and Trends of Pneumoconiosis in the Shandong Province, China, 1949–2022.
  * **An, B.** Impact of the US-China Tech War on China-EU Cooperation in Sustainable Energy Innovation: Evidence from Patents.
  * **An, B.** Community Enterprises in China: Development, Models and Policy Support.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
