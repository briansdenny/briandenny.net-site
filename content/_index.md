---
# Leave the homepage title empty to use the site title
title:
date: 2022-04-10
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: Workflow & Process Mapping
          description:
          icon: diagram-project
          icon_pack: fas
        - name: Statistics & Analysis
          description:
          icon: chart-line
          icon_pack: fas
        - name: Data Collection & Refinement
          description:
          icon: database
          icon_pack: fas
        - name: Quantitative & Qualitative Research
          description:
          icon: magnifying-glass
          icon_pack: fas
        - name: Teaching & Learning
          description:
          icon: chalkboard-user
          icon_pack: fas
        - name: Writing & Editing
          description:
          icon: marker
          icon_pack: fas 
  - block: experience
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
        - title: Senior Technical Writer
          company: Consensus Cloud Solutions, Inc.
          company_url: ''
          company_logo: 
          location: California
          date_start: '2022-03-21'
          date_end: ''
          description: |2-
              * Spearheading collaborative and sustainable digital adoption CLM practices while designing and implementing expanded microcontent across multiple brands.
              * Creating instructional guides for digital adoption microcontent creators on WCAG compliance and the use of CSS, jQuery, and window variables for content segmentation.
              * Furthering a "Top 5" company goal by conducting market research on API developer community portals to inform future product development.
              * Reduced cancellations by 16% by designing, validating, implementing, and maintaining customer-facing digital adoption microcontent to supplement existing UI.
              * Interviewed internal stakeholders to create process chart of existing payment processing workflow to enable implementation of new fraud prevention tools.
        - title: Editor (academic)
          company: University of Michigan & University of California-Irvine
          company_url: ''
          company_logo:
          location: Michigan & California
          date_start: '2020-02-01'
          date_end: ''
          description: |2-
              * Conducting developmental, line, and copy editing for researcher-turned-professor's dissertation, presentations, academic articles, job market material, and grant proposals (one awarded $2.5 million and another likely to be awarded in 2023). 
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
        - name: Learning & Development
          tag: L&D
        - name: Technical Writing
          tag: TechWriting
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Have a question, comment, or feedback? Get in touch! I'd love to connect with you. 
      # Contact (add or remove contact options as necessary)
      email: briansdenny@gmail.com
      address:
        street: 
        city: Long Beach
        region: CA
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
