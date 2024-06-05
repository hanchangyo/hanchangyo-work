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
  - block: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Project Lecturer
          company: The University of Tokyo
          company_url: 'https://www.u-tokyo.ac.jp/'
          company_logo: utokyo-logo
          location: Tokyo, Japan
          date_start: '2024-04-01'
          date_end: ''
          description: HCI research
        - title: Assistant Professor
          company: The University of Tokyo
          company_url: 'https://www.u-tokyo.ac.jp/'
          company_logo: utokyo-logo
          location: Tokyo, Japan
          date_start: '2021-04-01'
          date_end: '2024-03-31'
          description: HCI research
        - title: JSPS Research Fellow (PD)
          company: The University of Tokyo
          company_url: 'https://www.u-tokyo.ac.jp/'
          company_logo: utokyo-logo
          location: Tokyo, Japan
          date_start: '2020-04-01'
          date_end: '2021-03-31'
          description: HCI research
        # - title: PhD course
        #   company: The University of Tokyo
        #   company_url: 'https://www.u-tokyo.ac.jp/'
        #   company_logo: utokyo-logo
        #   location: Tokyo, Japan
        #   date_start: '2017-04-01'
        #   date_end: '2020-03-31'
        #   description: |2-
        #     Thesis title: "Force Markers: Embossed Fiducials for Recognizing Physical Objects on PressureSensitive Touch Surfaces."
        - title: Researcher
          company: Electronics and Telecommunications Institute
          company_url: 'https://www.etri.re.kr'
          company_logo: etri-logo
          location: Daejeon, Korea
          date_start: '2013-04-01'
          date_end: '2016-09-01'
          description: space-division-multiplexed (SDM) optical communication systems, access network for mobile base stations
        # - title: Master's course
        #   company: The University of Tokyo
        #   company_url: 'https://www.u-tokyo.ac.jp/'
        #   company_logo: utokyo-logo
        #   location: Tokyo, Japan
        #   date_start: '2011-04-01'
        #   date_end: '2013-03-31'
        #   description: Research on high-speed optical communication systems
        # - title: Bachelor's course
        #   company: Tokyo Institute of Technology
        #   company_url: 'https://www.titech.ac.jp/'
        #   company_logo: tokyotech-logo
        #   location: Tokyo, Japan
        #   date_start: '2007-04-01'
        #   date_end: '2011-03-31'
        #   description: Electrical and Electronics Engineering course
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
        - name: Tangible UIs
          tag: TUIs
        - name: Robots
          tag: Robots
        - name: Wireless Power Transfer & Sensing
          tag: WPT
        - name: Media Techonologies
          tag: MediaTech
        - name: Optical Communications
          tag: OPTCOMM
        - name: Others
          tag: Others
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: collection
    id: publications
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

  - block: markdown
    id: awards
    content:
      title: Awards
      text: |
        - **IPSJ Interaction 2024** Interactive Presentation Award (participant vote) x 2
        - **IPSJ Interaction 2023** Interactive Presentation Award (participant vote)
        - **MVE2021** Award
        - **CHI2021** CHI'20@CHI’21 People’s Choice Best Demo Honorable Mention Award
        - **CHI2020** Honorable Mention Award
        - **IPSJ Interaction 2020** Interactive Presentation Award (participant vote)
        - **IPSJ Interaction 2020** Interactive Presentation Award (PC recommendation)
        - **TEI2020** Best Paper Award ACM
    design:
      columns: '2'

  - block: features
    content:
      title: Skills
      items:
        - name: Python
          description: Expert, GUI programming
          icon: python
          icon_pack: fab
        - name: Unity
          description: Intermediate
          icon: unity
          icon_pack: fab
        - name: MATLAB
          description: Expertise at DSP
          icon: code
          icon_pack: fas
        - name: Processing
          description: Visual programming
          icon: code
          icon_pack: fas
        - name: C++
          description: Mostly for Physical Computing
          icon: code
          icon_pack: fas
        - name: Fusion 360
          description: Expertise at design for 3D printing
          icon: cube
          icon_pack: fas
        - name: Rhinoceros + Grasshopper
          description: Parametric modeling
          icon: cube
          icon_pack: fas
        - name: ADS
          description: RF circuit simulation
          icon: gear
          icon_pack: fas          
        - name: AWRDE
          description: RF circuit simulation
          icon: gear
          icon_pack: fas          
        - name: HFSS
          description: FEM for microwave components
          icon: gear
          icon_pack: fas          
        - name: Korean
          description: Native
          icon: language
          icon_pack: fas          
        - name: Japanese
          description: JLPT 180/180
          icon: language
          icon_pack: fas          
        - name: English
          description: TOEIC 970/990
          icon: language
          icon_pack: fas          
    design:
      columns: '2'
 # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: accomplishments
  #   id: grants
  #   content:
  #     title: Grants
  #   design:
  #     columns: '1'

  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: grants
  #   content:
  #     title: Grants
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        
      # Contact (add or remove contact options as necessary)
      email: hanc@nae-lab.org
  #     phone: 888 888 88 88
  #     appointment_url: 'https://calendly.com'
      address:
        street: 91C, Faculty of Engineering Bldg. 2, 7-3-1, Hongo
        city: Bunkyo
        region: Tokyo
        postcode: '133-8656'
        country: Japan
        country_code: JP
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
  #     office_hours:
  #       - 'Monday 10:00 to 13:00'
  #       - 'Wednesday 09:00 to 10:00'
  #     contact_links:
  #       - icon: twitter
  #         icon_pack: fab
  #         name: DM Me
  #         link: 'https://twitter.com/Twitter'
  #       - icon: skype
  #         icon_pack: fab
  #         name: Skype Me
  #         link: 'skype:echo123?call'
  #       - icon: video
  #         icon_pack: fas
  #         name: Zoom Me
  #         link: 'https://zoom.com'
  #     # Automatically link email and phone or display as text?
  #     autolink: true
  #     # Email form provider
  #     form:
  #       provider: netlify
  #       formspree:
  #         id:
  #       netlify:
  #         # Enable CAPTCHA challenge to reduce spam?
  #         captcha: false
  #   design:
  #     columns: '2'
---
