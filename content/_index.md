---
# Leave the homepage title empty to use the site title
title: Yiping Ge
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: geyiping
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
        - title: M.S. in Cognitive Neuroscience
          company: Institute of Psychology, CAS
          company_url: 'http://www.psych.ac.cn/'
          company_logo: xls
          location: Beijing, China
          date_start: '2021-09-01'
          date_end: ''

        - title: Summer Internship
          company: Peking University
          company_url: 'https://www.pku.edu.cn/'
          company_logo: pku
          location: Beijing, China
          date_start: '2020-07-01'
          date_end: '2020-08-30'
          # description: Taught electronic engineering and researched semiconductor physics.
        - title: Minor in Law School
          company: Central University of Finance and Economics
          company_url: 'https://www.cufe.edu.cn/'
          company_logo: cufe
          location: Beijing, China
          date_start: '2018-09-01'
          date_end: '2021-06-30'
          description: TA in Constitution Class
        - title: B.S. in Applied Psychology
          company: Central University of Finance and Economics
          company_url: 'https://www.cufe.edu.cn/'
          company_logo: cufe
          location: Beijing, China
          date_start: '2017-09-01'
          date_end: '2021-06-30'
    design:
      columns: '2'
  
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
        exclude_featured: true
    design:
      columns: '2'
      view: compact
  - block: collection
    id: pulications
    content:
      title: Recent Publications
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
  - block: skills
    id: academicskills
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Academic&nbsp;Skills'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Languages
          images: hi
          subtitle: Chinese(native), English(Fluent, IELTS:7.5)
        - title: Data collection
          images: nice
          subtitle: MATLAB, Psychophysics Toolbox, E-prime, BIOPAC MP160
        - title: Data analysis
          images: yeah
          subtitle: MATLAB, SPSS, R
        - title: Graphics
          images: love
          subtitle: MATLAB, Adobe lllustrator, Photoshop

        
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Welcome to reach out!
      # Contact (add or remove contact options as necessary)
      email: geyp@psych.ac.cn
      address:
        street: No.16 LinCui Rd.
        city: Chaoyang District
        region: Beijing
        postcode: '100101'
        country: China
        country_code: CN
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: \@Yiping_Ge
          link: 'https://twitter.com/Yiping_Ge'
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---