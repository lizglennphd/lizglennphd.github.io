---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-06-25
type: landing

design:
  # Default section spacing
  spacing: "6rem"

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
  - block: markdown
  - id: consulting
    content:
      title: 'Consultation Services'
      subtitle: 'Data Analysis / Statistics'
      text: 'Specialties: 
      - Structural Equation Modelling: How do these variables influence each other? In these models, we can also use latent variable modelling to increase precision of our findings. This includes mediation and moderation models.  
      - Latent Variable Modelling (Confirmatory Factor Analysis): How do individual data sources represent or measure larger theoretical concepts (latent variables)?
      - Latent Growth Curve Modelling: Are there changes in these variables over time? Do certain variables or interventions impact change?
      - Latent Profile Analysis: Within this population, are there distinct groups based on certain characteristics (variables)?'
      subtitle: 'Data Science'
      text: ' I use the tidyverse suite in R to make the best use of existing data.
      - Webscraping: Extracting data from online sources into a spreadsheet that can be used for decision making, data visualizations, or data analyses.
      - Text-Based Data: Turning qualitative data into a quantitative format. Qualitative data is usually from interview transcripts or free response items.
      - Data Visualization: Bringing data to life using graphics. I can adjust color schemes and font to match your institution or business branding
      - Data Cleaning and Creation: Turning raw data into variables that are useful in analyses.
      - Data Missingness: There are many approaches to data missingness, which is often dependent on your data and analytic plan. I am familiar with a range of imputation methods to help create full datasets when needed, or the use of analytic approaches that account for missingness (FIML).'
      
      subtitle: 'Research Design and Clinical Trials'
      text: 'TEXT HERE'
      subtitle: 'Fees'
      text: '
      - Hourly Rate = $75/hr
      - Discounted price available for graduate students and early career researchers ($50/hr).
      - Data Analysis projects resulting in a full manuscript usually take around 20 hours. 
      - Once a manuscript is submitted, I will not charge for minor edits during the revision process. If manuscript revisions require a major change in analytic or research approach, we may need to re-initiate a contract or invoice. 
      - I can accept checks or online payment (3% processing fee)'
---
