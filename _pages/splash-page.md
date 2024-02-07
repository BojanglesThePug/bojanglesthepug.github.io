---
title: Welcome
layout: splash
permalink: /splash-page/
date: 2024-02-06T02:02:00-08:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/bobo-smiling.jpg
  actions:
    - label: "Visit my website BoboPug.com"
      url: "https://bobopug.com/"
  caption: "Photo credit: [**Alexis**]"
excerpt: "To my blog! Here you will find fine selections of puggo photos - some with special guest Ponyo pug!"
intro: 
  - excerpt: '*How you doin?*<br>*I&rsquo;m pugg&rsquo;n awesome!*<br>__-somepuggy 2024__'
feature_row:
  - image_path: assets/images/bobo-aprehensive.jpg
    image_caption: "Image courtesy of [Alexis]"
    alt: "aprehensive puggo"
    title: "Aprehensive Puggo"
    excerpt: "Behold, a glamour shot of me! Your favorite puggo!"
  - image_path: /assets/images/bobo-eyeball.jpg
    image_caption: "Image courtesy of [Justin]"
    alt: "big eyeball bobo"
    title: "Bobo Big Eyeballs"
    excerpt: "Look at me and my big o' eyeballs"
  - image_path: /assets/images/meSisterPonyo.jpg
    image_caption: "Image courtesy of [Justin]"
    title: "Me sister Ponyo!"
    excerpt: "She's like a refugee in our house or something."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
