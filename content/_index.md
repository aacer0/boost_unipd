---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Boost Lab
      image:
        filename: home.jpg
      text: |-
        <div style="font-size:large">You can’t do inference or data compression without making hypotheses.
        But every hypotheses will influence the information extracted from the data.

        In order to reduce the bias with which the data are analyzed, one should be well aware about the underlying assumptions 
        and at the same time those should be kept to the essential.
        This attitude requires advanced technological and statistical tools to tackle the arduous challenges posed by the management, processing and analysis of large and complex datasets.

        This is the core business of **BOOST**.
        Our main applications are in **High Energy Physics** and **Data-Driven Medicine**.</div>
        
#    design:
#      background:
#        gradient_end: '#1976d2'
#        gradient_start: '#004ba0'
#        text_color_light: true
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
      view: compact
      columns: '2'
  - block: portfolio
    id: people
    content:
      title: People
      filters:
        folders:
          - people
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
        - name: Faculty Members
          tag: Faculty Members
        - name: Other
          tag: Demo
      sort_by: 'Date'
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    id: publications
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
      view: compact
  - block: collection
    id: events
    content:
      title: Recent & Upcoming Events
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      columns: '2'
      view: compact   
  - block: collection
    id: thesis
    content:
      title: Thesis
      filters:
        folders:
          - thesis
    design:
      columns: '2'
      view: compact      
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: boost.unipd@gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: Via Francesco Marzolo, 8, 35121 Padova PD <br>
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d700.2514157756318!2d11.885703661760342!3d45.40922537733434!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x477eda585918ab75%3A0x76d6424a9b793480!2sUniversit%C3%A0%20Degli%20Studi%20di%20Padova%20-%20Dipartimento%20di%20Fisica%20e%20Astronomia%20G.%20Galilei!5e0!3m2!1sit!2sit!4v1661268231623!5m2!1sit!2sit" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        #city: Padova
        #region: CA
        #postcode: '35121'
        #country: Italy
        #country_code: IT
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---