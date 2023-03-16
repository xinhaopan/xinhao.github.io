---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2016
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Exchange student
          company: University of Groningen
          company_url: 'https://www.rug.nl/?lang=en'
          company_logo: org-gc
          location: Groningen, Netherlands
          date_start: '09/2022'
          date_end: '02/2023'
          
        - title: Exchange student
          company: University of Groningen
          company_url: 'https://www.rug.nl/?lang=en'
          company_logo: org-gc
          location: Groningen, Netherlands
          date_start: '09/2022'
          date_end: '02/2023'

    design:
      columns: '2'
  
---
