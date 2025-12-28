---
title: Nagpal Lab
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Nagpal
        Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        We study microbiome–brain communication across development, with a focus on stress and social behaviour. Using zebrafish, _C. elegans_, and translational frameworks, our work integrates neurobiology, microbiome science, and environmental exposures.

  - block: markdown
    content:
      title: Research themes
      text: |
        - Microbiome–brain communication and neurodevelopment  
        - Stress physiology and social behaviour  
        - Environmental exposures (exposome) and resilience  
        - Cross-species discovery: zebrafish and _C. elegans_

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: collection
    content:
      title: Latest News
      count: 5
      page_type: post
      order: desc
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'
---
