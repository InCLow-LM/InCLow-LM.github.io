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
        
        Welcome to our homepage! InCLow stands for Interpretable, Cognitively inspired, Low-resource Language Models.

        We are a thriving research team working at the intersection of natural language processing and (cognitive) linguistics. Our [projects](https://inclow-lm.github.io/projects/) revolve around two key questions:

        - How to develop language technologies that work well for a large variety of languages?
        
        - What can we learn about human language while attempting to do that?

        <p>We’re proudly part of the larger Computational Linguistics group
        <span style="line-height: 1.5; display: inline-flex; align-items: center;">
        <img src="https://raw.githubusercontent.com/InCLow-LM/InCLow-LM.github.io/refs/heads/main/assets/media/gronlp.png" alt="GroNLP logo" style="height: 1em; vertical-align: middle; margin-right: 0.3em;">
        <a href="https://www.rug.nl/research/clcg/research/cl/">GroNLP</a>
        </span>
        at the University of Groningen, the Netherlands.
        </p>

        (P.S. Great appreciation to [Maria Pilar Uribe-Silva](https://www.linkedin.com/in/maria-pilar-uribe-silva) for the perfect team photograph!)

  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 2
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'

  - block: markdown
    content:
      title: Latest News
      subtitle:
      text: |
        [05/23/2025] Hello world 2.

        [04/03/2025] Hello world 1.

        [03/02/2025] Hello world 0.

    design:
      columns: '1'

  # - block: collection
  #   content:
  #     title: Latest Publications
  #     text: ""
  #     count: 6
  #     filters:
  #       folders:
  #         - publication
  #       # publication_type: 'article'
  #   design:
  #     view: citation
  #     # view: card
  #     columns: '1'


  - block: collection
    content:
      title: People
      text: ""
      # count: 10
      filters:
        folders:
          - authors
        # publication_type: 'article'
    design:
      view: card
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
