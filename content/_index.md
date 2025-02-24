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
        - name: Python
          description: Pytorch, Tensorflow, Numpy, Pandas, OpenCV, PIL and etc.
          icon: python
          icon_pack: fab
        - name: Matlab
          description: Statistics Tools, Signal Processing Tools, PDE solvers.
          icon: chart-line
          icon_pack: fas
        - name: Xcode/Fultter
          description: IOS/Android development, UI Controller Design.
          icon: app-store-ios
          icon_pack: fab
        - name: Deep Learning Model
          description: CNNs, Swin Transformer, GAN, Diffusion Model.
          icon: microchip
          icon_pack: fas
        - name: Computer Vision
          description: Image Generation, Object Detection, Image and Video Compression, Pose Estimation, Segmentation.
          icon: eye
          icon_pack: fas
        - name: Photography
          description: Photoshop, Premiere Pro, After Effect, Final Cut Pro, Unity.
          icon: camera-retro
          icon_pack: fas
          


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
#        - name: All
#          tag: '*'
        - name: Image/Video Compression
          tag: Compression
        - name: Generation Model
          tag: generation
        - name: Bilibili/Youtube
          tag: Bilibili
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      

  - block: collection
    content:
      title: Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation


#  - block: experience
#    content:
#      title: Experience
#      # Date format for experience
#      #   Refer to https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
#      # Experiences.
#      #   Add/remove as many `experience` items below as you like.
#      #   Required fields are `title`, `company`, and `date_start`.
#      #   Leave `date_end` empty if it's your current employer.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - title: CEO
#          company: GenCoin
#          company_url: ''
#          company_logo: org-gc
#          location: California
#          date_start: '2021-01-01'
#          date_end: ''
#          description: |2-
#              Responsibilities include:
#
#              * Analysing
#              * Modelling
#              * Deploying
#        - title: Professor of Semiconductor Physics
#          company: University X
#          company_url: ''
#          company_logo: org-x
#          location: California
#          date_start: '2016-01-01'
#          date_end: '2020-12-31'
#          description: Taught electronic engineering and researched semiconductor physics.
#    design:
#      columns: '2'
#      


      

#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://wowchemy.com/docs/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
  


#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'

#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
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

#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: Tshen2@scu.edu
      phone: 669 302 0695
#      appointment_url: 'https://calendly.com'
#      address:
#        street: 450 Serra Mall
#        city: Stanford
#        region: CA
#        postcode: '94305'
#        country: United States
#        country_code: US
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
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
