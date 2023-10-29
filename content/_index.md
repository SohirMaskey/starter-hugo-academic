---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: papers
    content:
      title: Papers
      filters:
        folders:
          - papers
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: collection
    id: papers
    content:
      title: Papers
      filters:
        folders:
          - papers
    design:
      columns: '2'
      view: compact

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: other
    content:
      title: Other
      filters:
        folders:
          - other
        exclude_featured: true
    design:
      columns: '2'
      view: citation
---
