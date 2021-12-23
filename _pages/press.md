---
layout: archive
title: "Press"
permalink: /press/
author_profile: true
---

Sun, Rachel. [“WSU Anthropologists Work With Kalispel Tribe To Learn About Traditional Foods.”](https://www.nwpb.org/2021/12/02/wsu-anthropologists-work-with-kalispel-tribe-to-learn-about-traditional-foods/?fbclid=IwAR1_CifmkCbYg4q8HhZ2uvgSkMWh_rGzdHUx3G-HssFG1rJ9cM15tumR9Mk) *Northwest Public Broadcasting.* December 2, 2021

Brown, Sydney. [“What would you eat 500 years ago in the Pacific Northwest?”](https://www.spokesman.com/stories/2021/nov/25/what-could-you-eat-in-500-years-ago-in-the-pnw/) *The Spokesman Review.* November 25, 2021

Hunter, AnneMarie. [“Through the Camas Plant, Archaeologist Bridges the Past, Present, and Future.”](https://foundation.wsu.edu/2021/11/01/through-the-camas-plant-archaeologist-bridges-the-past-present-and-future/) Washington State University Foundation. November 1, 2021


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
