---
# Leave the homepage title empty to use the site title
title:
date: 2023-5-20
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: featured
    content:
      title: Publication Preprint
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card

  - block: portfolio
    id: projects
    content:
      title: Ongoing Publication and Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Reinforcement Learning
          tag: Reinforcement Learning
        - name: Deep Learning
          tag: Deep Learning
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: markdown
    content:
      title: Awards
      subtitle: "Award: 1) First place award of poster competition for PhD students in 2023 Statistics and Optimization in Data Science Workshop at Mitchell E. Daniels, Jr. School of Business. 2) Magna Cum Laude of New York University 3) Dean’s List of the Academic Year of New York University."
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
---
