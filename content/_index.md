---
# Leave the homepage title empty to use the site title
title:
date: 2024-07-12
type: landing

sections:
  - block: hero
    content:
      title: PID4NFDI
      image:
        filename: pid4nfdi.png
      text: |-
        PID4NFDI is a basic service for persistent identifiers in development for Germany's national research data infrastructure, the [Nationale Forschungsdateninfrastruktur (NFDI)](https://www.nfdi.de/?lang=en). PID4NFDI is part of [Base4NFDI](https://base4nfdi.de/) and is currently in its initialisation phase, the first of three service development phases.

        Persistent identifiers (PIDs) are central to FAIR research data management. However, different disciplines and different resources result in diverse requirements and the different NFDI consortia have different levels of maturity in PID implementation. PID4NFDI will design a work programme to build an NFDI foundation service on established PID infrastructures.
  
  - block: collection
    content:
      title: Latest Blog Posts
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
        folders:
          - blog
      offset: 0
      order: desc
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publications
        #publication_type: 'article'
    design:
      view: list
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
