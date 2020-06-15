---
layout: splash
permalink: /gallery/
title: "Photo gallery"
author_profile: false
gallery:
  - url: /assets/images/gallery/samples.jpeg
    image_path: /assets/images/gallery/samples.jpeg
    alt: "samples"
    title: "Collecting wolf saliva can be challeging"
---

<style>
  img{
      max-width:400px;
      max-height:300px;
      OBJECT-FIT:contain;
  }
  .mfp-title {
    text-align:center;
    font-size:2em;
    line-height:35px
  }
</style>

<h2 align="center"> Photo Gallery </h2>

{% include gallery id="gallery" class="gallery-thumbnail"  %}
