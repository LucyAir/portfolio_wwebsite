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

              * Used voter file and vote history data to construct election turnout models.
              * Used R to create an R markdown file that generated campaign donor information utilizing New York State Board of Elections campaign finance filings. The document provided insight into the geographic placement and number of in-district donors.

        - title: Electoral Polling Intern
          company: Data for Progress
          company_url: 'https://www.dataforprogress.org'
          company_logo: dfp
          location: Washington D.C.
          date_start: '2022-09-01'
          date_end: '2023-01-31'
          description: |2-
              Responsibilities include:

              * Created and maintained a dataset of potential and announced Democratic candidates for state office. 
              * Led a project that looked to analyze trends regarding support for the Independent Legislature Theory and legislative involvement in electoral administration. Independently wrote survey questions and produced reports on findings that included data visualizations.     
              * Worked with senior staff to design and field a survey for a prospective Virginia State Senate candidate. Assisted in writing questions for the candidate to better understand constituent concerns and needs. 
        - title: Undergraduate Researcher
          company: University of Florida Election Lab
          company_url: 'https://electionscience.clas.ufl.edu'
          company_logo: uf
          location: Gainesville, Florida
          date_start: '2021-01-01'
          date_end: '2023-03-31'
          description: |2-
              Responsibilities include:

              * Led a project on the impact of Covid-19 on youth voter turnout on college campuses. Utilized voter file data and a difference-in-difference analysis to conclude that the Covid-19 campus evacuation order suppressed primary turnout when compared to youth voters in the surrounding area. 
              * Performed data integration using a Python script that matched information from election observer volunteer documents to their voter file data.
              * Conducted research on behalf of the League of Women Voters on redistricting maps in Florida. Studied the Voting Rights Act to look for violations in the maps proposed by the state government. 

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
