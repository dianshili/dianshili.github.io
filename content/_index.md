---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Dianshi (Moses) Li
      image:
        filename: welcome.jpg
      text: |
        <br>

        Ph.D. student at the University of Macau focused on **computational social science**, **quantitative methodology**, **applied statistics**, **criminology**, and **AI for medicine**.

        I work with the Centre for Empirical Legal Studies Laboratory to deliver data-driven insights for law and society. Explore my research, publications, and collaborations below.

  - block: collection
    content:
      title: Latest News
      subtitle: "Updates from my research and collaborations"
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
      title: Research Interests
      subtitle: ''
      text: |
        - Computational Social Science
        - Quantitative Methodology
        - Applied Statistics
        - Criminology
        - AI for Medicine
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
      title: Publications
      subtitle:
      text: |
        I maintain an up-to-date list of my articles on Google Scholar, including links to download or access each paper. You can browse the full list here: [Google Scholar Profile](https://scholar.google.com/citations?user=ZDgJsy8AAAAJ&hl=en&authuser=1).

        {{% cta cta_link="./publication/" cta_text="View selected publications →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
