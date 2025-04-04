---
type: PageLayout
title: About
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg4.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    text: >+
      # HHey, I’m a MERN stack developer. I build and scale full-stack applications with MongoDB, Express, React, and Node.js. Currently exploring new opportunities, When I’m not coding, debugging, or deploying, I’m probably enjoying a bowl of cereal. 

    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Hero image
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-12
          - pl-4
          - pr-4
        textAlign: left
    type: HeroSection
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'I worked with these folks:'
    images:
      - type: ImageBlock
        url: /images/ajeya-dark.webp
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/logo_srm_white.png
        altText: Logo two
        caption: Logo two
    spacing: 3
    columns: 5
    aspectRatio: auto
    showCaption: false
    enableHover: false
    styles:
      self:
        width: wide
        height: auto
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    subtitle: 'You can find me here:'
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/rohi1011'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/in/rohithr10/'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://www.instagram.com/'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 16
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'React'
      - type: Label
        label: Node
      - type: Label
        label: MongoDB
      - type: Label
        label: Express
      - type: Label
        label: AWS
      - type: Label
        label: Docker
      - type: Label
        label: Jenkins
      - type: Label
        label: Linux
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [rrohith1011@gmail.com](mailto:rrohith1011@gmail.com)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * Software Developer @SRM Tech 

          **2020-2021**

          * Sofware Developer @Ajeya Infosol
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2015-2018**

          * BSc Computer Science from VIT, Vellore


          **2018-2020**

          * MSc Computer Science from Loyola College, Chennai
        styles:
          self:
            textAlign: left
    columns: 2
    spacingX: 60
    spacingY: 60
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        textAlign: left
  # - type: DividerSection
  #   styles:
  #     self:
  #       width: wide
  #       padding:
  #         - pt-12
  #         - pb-12
  #         - pl-4
  #         - pr-4
  #       borderWidth: 1
  #       borderStyle: solid
  # - type: ContactSection
  #   backgroundSize: full
  #   title: "Let’s talk... \U0001F4AC"
  #   colors: colors-f
  #   form:
  #     type: FormBlock
  #     elementId: sign-up-form
  #     fields:
  #       - name: firstName
  #         label: First Name
  #         hideLabel: true
  #         placeholder: First Name
  #         isRequired: true
  #         width: 1/2
  #         type: TextFormControl
  #       - name: lastName
  #         label: Last Name
  #         hideLabel: true
  #         placeholder: Last Name
  #         isRequired: false
  #         width: 1/2
  #         type: TextFormControl
  #       - name: email
  #         label: Email
  #         hideLabel: true
  #         placeholder: Email
  #         isRequired: true
  #         width: full
  #         type: EmailFormControl
  #       - name: message
  #         label: Message
  #         hideLabel: true
  #         placeholder: Tell me about your project
  #         isRequired: true
  #         width: full
  #         type: TextareaFormControl
  #       - name: updatesConsent
  #         label: Sign me up to recieve my words
  #         isRequired: false
  #         width: full
  #         type: CheckboxFormControl
  #     submitLabel: "Submit \U0001F680"
  #     styles:
  #       self:
  #         textAlign: center
  # styles:
  #   self:
  #     height: auto
  #     width: narrow
  #     margin:
  #       - mt-0
  #       - mb-0
  #       - ml-4
  #       - mr-4
  #     padding:
  #       - pt-12
  #       - pb-12
  #       - pr-4
  #       - pl-4
  #     flexDirection: row
  #     textAlign: left
---
