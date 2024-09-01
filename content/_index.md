---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-01
type: landing

sections:
  - block: markdown
    content:
      title: "The Dodge Lab @ SFU"
      subtitle: "Time-Resolved Optical Spectroscopy of Quantum Materials"

    design:
      columns: '1'

    spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["30px", "0", "0px", "0"]

    background:
      image: NarrowCrop_SunPainting_DSC_1496_AS.jpg
      image_darken: 0.5
      image_parallax: true
      image_position: center
      image_size: cover
      text_color_light: true

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
