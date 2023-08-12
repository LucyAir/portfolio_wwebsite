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
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 
          icon: chart-line
          icon_pack: fas
        - name: Overleaf
          description: 
          icon: overleaf
          icon_pack: ai
        - name: Research
          description: 
          icon: book-open
          icon_pack: fas
        - name: QGIS
          description: 
          icon: q
          icon_pack: fas
        - name: Python
          description: 
          icon: python
          icon_pack: fab
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Data Analyst
          company: New York Senate Democratic Campaign Committee
          company_url: 'https://www.newyorksenatedems.com'
          company_logo: nyseal
          location: New York, New York
          date_start: '2023-04-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Building district databases
              * Generating informative maps
        - title: Electoral Polling Intern
          company: Data for Progress
          company_url: 'https://www.dataforprogress.org'
          company_logo: dfp
          location: Washington D.C.
          date_start: '2022-09-01'
          date_end: '2023-01-31'
          description: |2-
              Responsibilities include:

              * Built a national database of potential democratic candidates
              * Developed surveys based on client requests
        - title: Undergraduate Researcher
          company: University of Florida Election Lab
          company_url: 'https://electionscience.clas.ufl.edu'
          company_logo: uf
          location: Gainesville, Florida
          date_start: '2021-01-01'
          date_end: '2023-03-31'
          description: |2-
              Responsibilities include:

              * Conducted research on voter tunrout and behavior
              * Built redistricting maps
    design:
      columns: '2'

  - block: portfolio
    id: projects
    content:
      title: Projects
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
        - name: Election Science
          tag: ElectionSci
        - name: Blog Posts
          tag: Blog
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: payton.lussier@outlook.com
      phone: +1 (954) 234-4101
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netflify
        formspree:
          id:
        netlify: 
          # Enable CAPTCHA challenge to reduce spam?
          captcha: true
    design:
      columns: '2'
---
