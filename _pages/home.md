---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/wct_banner_base-h500-no-text.png
  actions:
    - label: "<i class='fas fa-download'></i> Install now"
      url: "https://webcuratortool.readthedocs.io/en/latest/guides/quick-start-guide.html#installation"
excerpt: >
  Open-source workflow management for selective web archiving<br />
feature_row:
  - image_path: /assets/images/quickstart.png
    alt: "guide"
    title: "Quick start guide"
    excerpt: "How to quickly get started using the WCT"
    url: "https://webcuratortool.readthedocs.io/en/latest/guides/quick-start-guide.html"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/features.png
    alt: "features"
    title: "WCT features"
    excerpt: "Check out the latest WCT features and see what's on the roadmap"
    url: "/features/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/community.png
    alt: "community"
    title: "Community"
    excerpt: "Join us to learn about or contribute to the WCT"
    url: "/about/collaboration/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---

{% include feature_row %}

{% for post in site.posts limit:1 %}
     {% include archive-single-home.html %}
  {% endfor %}