---
# Leave the homepage title empty to use the site title
title:
date: 2024-12-12
type: landing

sections:
  - block: hero
    content:
      title: Welcome to the <br> Uveitis dataset.
      image:
        filename: manuscript_scheme.png
      text:

  - block: markdown
    content:
      title:
      text: |
        This is the corresponding website to the publication [Intraocular dendritic cells characterize HLA-B27-associated acute anterior uveitis](https://doi.org/10.7554/elife.67396) 
        by Kasper et al., *eLife* 2021. We present single cell RNA-sequencing data intraocular liquid from HLA-B27-positive and -negative uveitis patients.
        The raw sequencing are available via [GEO GSE178833](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE178833).

  - block: collection
    id: datasets
    content:
      title: Dataset
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
      page_type: datasets
    design:
      view: showcase
      columns: '1'
      flip_alt_rows: false

  - block: markdown
    id: contact
    content:
      title: Contact
      text: |
        If you have any questions, please contact us via [mheming.com](https://www.mheming.com).
---
