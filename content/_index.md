---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          # filename: banner.jpg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: teaching
    content:
      title: Teaching
      subtitle: "Current Classes"
      text: |-
        #### Current Classes (Summer Term 2024)

        | Topic | Location | |
        | ----- | ------ | --- |
        | Lecture: *Numerik 2 (des maschinellen Lernens)* | :microphone: Mo 11-13 im F3001 und Do 9-11 im C112 | [Moodle](https://moodle.tu-ilmenau.de/course/view.php?id=1159), [Skript](https://www.janheiland.de/script-ndml/) |
        | Exercise: *Wissenschaftliches Rechnen* | :microphone: Mo 15-17 im C115 | [Moodle](https://moodle.tu-ilmenau.de/course/view.php?id=1626) |
        | Exercise: *Numerische Mathematik* | :microphone: Mo 13-15 im HU129 | [Moodle](https://moodle.tu-ilmenau.de/course/view.php?id=1115) |
  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Grants, Bachelor/Master/PhD Projects, and others.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: blog
    content:
      title: Blog Posts 
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
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
      # view: date-title-summary
      view: article-grid
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
