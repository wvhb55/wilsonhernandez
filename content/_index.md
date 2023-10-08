---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Bio
    username: admin
  id: about


- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      [Filtering publications](./publication/).
      {{% /callout %}}
    title: Research
  design:
    columns: "2"
    view: citation


- block: portfolio
  content:
    default_button_index: 0
    filters:
      folders:
      - project
    title: Current projects
  design:
    columns: "2"
    flip_alt_rows: false
    view: showcase
  id: projects


title: null
type: landing
---
