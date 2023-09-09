---
date: "2022-10-24"
sections:
# - block: hero
#   content:
#     cta:
#       label: '**Get Started**'
#       url: https://wowchemy.com/templates/
#     cta_alt:
#       label: Ask a question
#       url: https://discord.gg/z8wNYzb
#     cta_note:
#       label: '<div style="text-shadow: none;"><a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-themes"
#         data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star
#         Wowchemy Website Builder</a></div><div style="text-shadow: none;"><a class="github-button"
#         href="https://github.com/wowchemy/starter-hugo-academic" data-icon="octicon-star"
#         data-size="large" data-show-count="true" aria-label="Star">Star the Academic
#         template</a></div>'
#     image:
#       filename: hero-academic.png
#     text: |-
#       <!--Custom spacing-->
#       <div class="mb-3"></div>
#       <!--GitHub Button JS-->
#       <script async defer src="https://buttons.github.io/buttons.js"></script>
#     title: Hugo Academic Theme
#   design:
#     background:
#       gradient_end: '#1976d2'
#       gradient_start: '#004ba0'
#       text_color_light: true
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
      - name: Python
        description: Intermediate
        icon: python
        icon_pack: fab
      - name: Stata
        description: Advanced
        icon: stata
        icon_pack: custom
      - name: Matlab
        description: Advanced
        icon: matlab
        icon_pack: custom
      - name: ArcGIS
        description: Intermediate
        icon: arcgis
        icon_pack: custom
      - name: R
        description: Intermediate
        icon: r-project
        icon_pack: fab
      - name: QGIS
        description: Intermediate
        icon: qgis
        icon_pack: custom
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Federal Economic Competition Commission
      company_logo: cofece
      company_url: "https://www.cofece.mx/?lang=en"
      date_end: "2019-01-15"
      date_start: "2015-07-01"
      description: |2-
          Responsibilities include:
          * Conduct market studies
          * Econometric Analysis
      location: Mexico City
      title: Director of Economic Analysis
    - company: Mexican Social Security Institute
      company_logo: imss
      company_url: "http://www.imss.gob.mx/"
      date_end: "2013-07-31"
      date_start: "2011-01-01"
      description: 
      title: Research Analyst
    title: Professional Experience
  design:
    columns: "2"
  id: experience
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: University of Houston
      company_logo: uh
      company_url: ""
      date_end: "2023-08-10"
      date_start: "2023-07-10"
      description: Taught Principles of Microeconomics
      location: Houston, TX
      title: Instructor 
    - company: University X
      company_logo: uh
      company_url: ""
      date_end: "2022-08-10"
      date_start: "2022-07-01"
      description: Taught Principles of Macroeconomics
      location: Houston, TX
      title: Instructor
    title: Teaching Experience
  design:
    columns: "2"
  id: teaching
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Hobby School of Public Affairs, UH
      company_logo: uh
      company_url: ""
      date_end: ""
      date_start: "2022-09-01"
      description: 
      location: Houston, TX
      title: Research Assistant
    - company: Department of Economics, UH
      company_logo: uh
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: RA of Prof. Steve Craig
      location: Houston, TX
      title: Research Assistant
    - company: El Colegio de Mexico
      company_logo: colmex2  
      company_url: ""
      date_end: "2011-07-31"
      date_start: "2010-04-01"
      description: RA of PhD Gerardo Esquivel Hernandez
      location: Mexico City
      title: Research Assistant
    - company: UNAM
      company_logo: unam  
      company_url: ""
      date_end: "2011-06-30"
      date_start: "2010-05-01"
      description: RA of PhD Noemi Levi Orlik
      location: Mexico City
      title: Research Assistant
    title: Research Experience
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: ''
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Center for Research and Teaching in Economics
      organization_url: https://www.cide.edu/
      title: Econonomic Competition
      url: ""
    - certificate_url: 
      date_end: "2015-12-21"
      date_start: "2015-07-01"
      description: ""
      organization: Universidad Iberoamericana
      organization_url:  https://ibero.mx/
      title: Managerial Skills
      url: ""
    subtitle: null
    title: Certificates
  design:
    columns: "2"
# - block: collection
#   content:
#     count: 5
#     filters:
#       author: ""
#       category: ""
#       exclude_featured: false
#       exclude_future: false
#       exclude_past: false
#       folders:
#       - post
#       publication_type: ""
#       tag: ""
#     offset: 0
#     order: desc
#     subtitle: ""
#     text: ""
#     title: Recent Posts
#   design:
#     columns: "2"
#     view: compact
#   id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
# - block: markdown
#   content:
#     subtitle: ""
#     text: '{{< gallery album="demo" >}}'
#     title: Gallery
#   design:
#     columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
# - block: collection
#   content:
#     filters:
#       folders:
#       - event
#     title: Recent & Upcoming Talks
#   design:
#     columns: "2"
#     view: compact
#   id: talks
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: "2"
- block: contact
  content:
    email: edloaeza@cougarnet.uh.edu.com
    address:
      city: Stanford
      country: United States
      country_code: US
      postcode: "94305"
      region: CA
      street: 450 Serra Mall
      appointment_url: https://calendly.com
      autolink: true
    phone: 888 888 88 88
    contact_links:
      - icon: twitter
        icon_pack: fab
        link: https://twitter.com/evadavinia
        name: DM Me
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    # form:
    #   formspree:
    #     id: null
    #   netlify:
    #     captcha: false
    #   provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    # subtitle: null
    # text: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
