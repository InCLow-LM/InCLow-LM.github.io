---
# Leave the homepage title empty to use the site title
title:
date: 2025-04-16
type: landing

sections:
  - block: hero
    content:
      # title: InCLow Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **InCLow** is a research group at [CLCG](https://www.rug.nl/research/clcg/research/cl/members/list-of-members), University of Groningen. We are a group of people with the interest in (Multilingual) LM, model interpretability, BabyLM challenges.

        **Opening positions for 4-year PhD are available now! See [Here](https://www.rug.nl/about-ug/work-with-us/job-opportunities/?details=00347-02S000B8PP)**
  
  - block: collection
    content:
      title: Latest News
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
      page_type: post
    design:
      # view: card
      columns: '2'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        # publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

---
