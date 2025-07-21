---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-06-25
type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: lizg
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Research CV.pdf
    design:
      css_class: dark
      background: 
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: hero
    content:
      title: Consulting Services
      text: Partner with me on your next research project! I collaborate with academic researchers, especially early career researchers, on behavioral and psychological scientific projects, offering support with study design, methods, analysis, and publication.
      primary_action:
        text: Learn more | Get started
        url: /consulting
        icon: hero/chart-bar
  - block: resume-experience
    id: experience
    content:
      username: lizg
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: collection
    id: papers
    content:
      title: Publications
      text: "Full Text can be found on my [Research Gate](https://www.researchgate.net/profile/Elizabeth-Glenn-2) account"
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation


---

