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
        image: 
          filename: NarrowCrop_SunPainting_DSC_1496_AS.jpg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: true
          text_color_light: true
          alt_text: "Caustic network of spectral colors, part of Bob Miller's Sun Painting
          at The Exploratorium"

  - block: markdown
    content:
      title: false
      subtitle: ''
      text: "The Dodge Laboratory at Simon Fraser University examines the emergent quantum
      properties of materials using femtosecond pulses of light.
      
              * We employ **optical spectroscopy** to understand the physics of solids.
              
              * We focus on **quantum materials** such as superconductors, magnetic 
              materials, and topological electronic materials.
              
              * We are **experimentalists** with specialties in pulsed laser techniques 
              such as terahertz time-domain spectroscopy and  pump-probe spectroscopy."

    design:
      view: compact
      columns: '2'
      spacing:
        padding: ['40px', '0', '20px', '0']

  - block: markdown
    content:
      title: false
      subtitle: ''
      text: "<p style='font-size:0.667em;text-align: center;'> Header image: 
      <a href='https://www.exploratorium.edu/exhibits/sun-painting'><i>Sun Painting</i></a>, 
      by Bob Miller, © The Exploratorium, <a href='url'>www.exploratorium.edu</a></p>"

    design:
      view: compact
      columns: '1'
      spacing:
        padding: ['0px', '0', '0px', '0']
---
