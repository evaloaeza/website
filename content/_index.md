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
    title: About me
    username: admin
  id: about
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Working Papers
  design:
    columns: "2"
    view: card
  id: featured
- block: contact
  content:
    email: edloaeza@cougarnet.uh.edu
    address:
      city: Houston
      country: United States
      country_code: US
      postcode: "77204"
      region: TX
      street: 4104 Martin Luther King Blvd
      appointment_url: https://calendly.com
      autolink: true
    phone: 
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
