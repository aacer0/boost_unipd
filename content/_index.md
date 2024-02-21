---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    id: about
    content:
      title: BOOST Lab
      image:
        filename: home.jpg
      text: |-
        <div style="font-size:large">You can’t do inference or data compression without making hypotheses.
        But every hypotheses will influence the information extracted from the data.

        In order to reduce the bias with which the data are analyzed, one should be well aware about the underlying assumptions 
        and at the same time those should be kept to the essential.
        This attitude requires advanced technological and statistical tools to tackle the arduous challenges posed by the management, processing and analysis of large and complex datasets.

        This is the core business of **BOOST** (Boost Online Operations with advanced Statistics and Technology).
        Our main applications are in **High Energy Physics** and **Data-Driven Medicine**.</div>
        <div style="text-align:right; font-size:xx-small">Image Credit: D. Dominguez/CERN</div>
  # - block: collection
  #   id: research2
  #   content:
  #     title: Research activities
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 0
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - research
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: showcase
  #     columns: '1'
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
    id: research
    content:
      title: Research Activities
      filters:
        folders:
          - research
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
        - name: Data analysis
          tag: Data analysis
        - name: Machine learning
          tag: Machine learning
        - name: Hardware
          tag: Hardware
        - name: Quantum
          tag: Quantum
      sort_by: 'Date'
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
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
        - name: Ph.D. Students
          tag: PhD 
        - name: Other
          tag: Other
      sort_by: 'Date'
      sort_ascending: true
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: masonry
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
  # - block: collection
  #   id: externals
  #   content:
  #     title: External Collaborators
  #     filters:
  #       folders:
  #         - external
  #       exclude_featured: true
  #     sort_by: 'Title'
  #     sort_ascending: true 
  #   design:
  #     columns: '2'
  #     view: list
  - block: markdown
    id: externals
    content:
      title: External Collaborators
      text: <a href="mailto:emilio.meschi@cern.ch"><b>Emilio Meschi</b></a> - <a href="http://meschi.web.cern.ch/meschi/"><i>Principal Applied Physicist at CERN</i></a><br>       <a href="mailto:raffaele-tito.dagnolo@ipht.fr"><b>Raffaele Tito D'Agnolo</b></a> - <a href="https://www.ipht.fr/Phocea/Vie_des_labos/Ast/ast_visu.php?id_ast=865"><i>IPhT, Centre CEA de Saclay</i></a><br> <a href="mailto:gaiag795@mit.edu"><b>Gaia Grosso</b></a> - <a href="https://iaifi.org/current-fellows.html"><i>Fellow at IAIFI, MIT</i></a><br> <a href="mailto:maurizio.pierini@cern.ch"><b>Maurizio Pierini</b></a> - <a href="https://twitter.com/xmpierinix"><i>Senior Research staff at CERN</i></a><br> <a href="mailto:lorenzo.rosasco@unige.it"><b>Lorenzo Rosasco</b></a> - <a href="https://rubrica.unige.it/personale/UkNHXVxs"><i>Full Professor at Univeristy of Genova (MALGA)</i></a><br> <a href="mailto:wulzer@ifae.es"><b>Andrea Wulzer</b></a> - <a href="https://www.icrea.cat/Web/ScientificStaff/andrea-wulzer-380491"><i>ICREA Research Professor at Institut de Física d'Altes Energies (IFAE)</i></a><br>
    design:
      columns: '2'
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
  - block: portfolio
    id: teaching
    content:
      title: Teaching
      subtitle: <center><a href="http://physicsofdata.dfa.unipd.it/"><img src="img/logo_pod.png" alt="Physics of Data Logo" style="width:50%"></a></center>
      filters:
        folders:
          - teaching
    design:
      columns: '2'
      view: masonry   
#  - block: portfolio
#    id: theses
#    content:
#      title: Thesis offers
#      filters:
#        folders:
#          - thesis
#        exclude_featured: true
#    # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Master's Thesis
#          tag: master
#        - name: Bechelor's Thesis
#          tag: bechelor
#        #- name: Others
#        #  tag: Others
#      sort_by: 'Date'
#      sort_ascending: true    
#    design:
#      columns: '2'
#      view: list
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: boostlab@dfa.unipd.it #boost.unipd@gmail.com
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: Via Francesco Marzolo 8
        postcode: 35121 Padova PD
                <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d700.2514157756318!2d11.885703661760342!3d45.40922537733434!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x477eda585918ab75%3A0x76d6424a9b793480!2sUniversit%C3%A0%20Degli%20Studi%20di%20Padova%20-%20Dipartimento%20di%20Fisica%20e%20Astronomia%20G.%20Galilei!5e0!3m2!1sit!2sit!4v1661268231623!5m2!1sit!2sit" width="100%" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
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
