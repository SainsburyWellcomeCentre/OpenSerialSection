---
permalink: /registration/
title: "Registering serial section data"
layout: splash
excerpt: "Registering serial section data"
toc: false
header:
  overlay_color: "#000"
  overlay_filter: "0.3"
  overlay_image: /assets/images/registration/reg_banner.jpg
  actions:
    - label: "All repos"
      url: "https://github.com/orgs/SainsburyWellcomeCentre/teams/serial2p/repositories"

feature_row_ara_tools:
  - image_path: /assets/images/home/Registration.jpg
    url: "https://github.com/SainsburyWellcomeCentre/ara_tools"
    alt: "MATLAB based registration"
    title: "Elastix-based registration"
    excerpt: 'Registering images in MATLAB using Elastix'
    btn_label: "Enlarge image"
    btn_class: "btn--primary"

feature_row_amap:
  - image_path:  /assets/images/registration/NiftyReg_Logo.jpg
    alt: "NiftyReg Registration"
    title: "NiftyReg-based registration"
    excerpt: "Register brains to the Allen Atlas with NiftyReg"
    url: "https://github.com/SainsburyWellcomeCentre/aMAP/wiki"
    btn_label: "Read More"
    btn_class: "btn--primary"

---

{% include feature_row id="feature_row_ara_tools" type="left" %}
{% include feature_row id="feature_row_amap" type="left" %}