---
# Leave the homepage title empty to use the site title
title: VIBE Research Lab
summary: Viral Informatics, Biostatistics, and Evolution Research Lab at the CVR, University of Glasgow
date: 2024-09-07
type: landing

sections:
  - block: hero
    content:
      title: |
        VIBE Research Lab
      image:
        filename: vibetemp.png
      cta:
        label: Discover our Team
        url: /people
      cta_alt:
        label: Discover our Research
        url: /research
      text: |
        <br>
        
        <span style="font-size:0.9em;">Welcome to the **VIBE (Viral Informatics, Biostatistics, and Evolution)** Research Lab at the MRC-University of Glasgow Centre for Virus Research (CVR). Led by Dr Liam Brierley, we use newly emerging data and computational methods to investigate what drives the successful cross-species transmission of RNA viruses from one host species to another and how such traits evolve.</span>
         <br><br>
    
  - block: collection
    content:
      title: Latest Blog Posts
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: blog
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
          filename: cvr.jpg
          caption: 'Image: CM, 2017'
          focal_point: Right
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['0px', '0px', '0px', '0px']
      css_class: fullscreen
      
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

---
