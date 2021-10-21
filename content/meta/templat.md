---
title: Title
subtitle: Subtitle
excerpt: >-
  Multiline
date: 'YYYY-MM-DD'
thumb_image: images/{{img_thumb}}.jpg
thumb_image_alt: Alt text
image: images/{{img}}.jpg
image_alt: Alt text
seo:
  title: Title
  description: >-
    Description (Multiline)
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: Title
      keyName: property
    - name: 'og:description'
      value: >-
        Description (Multiline)
      keyName: property
    - name: 'og:image'
      value: images/{{img}}.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Title
    - name: 'twitter:description'
      value: >-
        Description (Multiline)
    - name: 'twitter:image'
      value: images/{{img}}.jpg
      relativeUrl: true
layout: post
---