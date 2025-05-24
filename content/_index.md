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
        <a href="https://www.rug.nl/research/clcg/research/cl/" style="height: 1em; vertical-align: middle; margin-right: 0.3em;">GroNLP</a>
        </span>
        at the University of Groningen, the Netherlands.
        </p>

        <p><i> <font size="4"> Appreciations to <a href="https://www.linkedin.com/in/maria-pilar-uribe-silva"> Maria Pilar Uribe-Silva </a> for the wonderful team photograph! </font> </i></p>

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
        **[May 2025]** [Jaap](https://jumelet.ai/) gave a [talk in Edinburgh](https://informatics.ed.ac.uk/ilcc/news-events/seminars-2025/friday-2nd-may-at-11am-jaap-jumelet) on [MultiBLiMP: A Multilingual Benchmark of Linguistic Minimal Pairs](https://arxiv.org/abs/2504.02768).
        
        **[May 2025]** Master student Anais Almendra from the University of Chile joined us for a 3-month visit. She works on morphological analysis of the endangered language Madupungun.
        
        **[April 2025]** [Jirui](https://betswish.github.io/) gave two talks at [KPN](https://www.kpn.com/algemeen/english) and [University of Amsterdam](https://www.uva.nl/en) on three topics on Retrieval Augmented Generation ([MIRAGE](https://aclanthology.org/2024.emnlp-main.347/), [likelihood gauges answer accuracy](https://aclanthology.org/2025.naacl-long.78/), and [Consistency in Multilingual Context Utilization](https://arxiv.org/abs/2504.00597))

        **[Mar 2025]** [Arianna](https://www.cs.rug.nl/~bisazza/) gave a keynote talk at [NoDaLiDa/Baltic-HLT 2025](https://sites.google.com/view/nodalida-bhlt2025/keynote-speakers), titled "Not all Language Models need to be Large: Studying Language Evolution and Acquisition with Modern Neural Networks".
        
        **[Feb 2025]** PhD student [Akari Haga](https://akari000.github.io/about/) from NAIST, Japan, joined us for a 6-month visit. She works on BabyLM-style models for Japanese.


    design:
      columns: '2'

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


  # - block: collection
  #   content:
  #     title: People
  #     text: ""
  #     # count: 10
  #     filters:
  #       folders:
  #         - authors
  #       # publication_type: 'article'
  #   design:
  #     view: card
  #     columns: '1'

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
