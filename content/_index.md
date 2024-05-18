---
# Leave the homepage title empty to use the site title
title: ''
type: landing

sections:
  - block: about.biography
    id: about
    content:
      username: admin
  - block: collection
    id: posts
    content:
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
          - event
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
  - block: markdown
    content:
      subtitle: ''
      text: |-
        {{< gallery album="nicholas" >}}
    design:
      columns: '1'
---
