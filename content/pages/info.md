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
    text: >-
      ## Hey I'm Theophilus, a developer. I was born and raised in Accra, Ghana, and that’s
      also where I’m based. I’m currently a free agent, ex-amalitech trainee, wordpress freelancer on fiverr. When I’m not coding, writing or watching a movie, I make music. I cook as well, but I'm better at eating ;).
    media:
      type: ImageBlock
      url: /images/me.JPEG
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
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
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
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: MediaGallerySection
    colors: colors-f
    subtitle: 'I worked with these folks:'
    images:
      - type: ImageBlock
        url: /images/logo1.svg
        altText: Logo one
        caption: Logo one
      - type: ImageBlock
        url: /images/logo2.svg
        altText: Logo two
        caption: Logo two
      - type: ImageBlock
        url: /images/logo3.svg
        altText: Logo three
        caption: Logo three
      - type: ImageBlock
        url: /images/logo4.svg
        altText: Logo four
        caption: Logo four
      - type: ImageBlock
        url: /images/logo5.svg
        altText: Logo five
        caption: Logo five
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
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
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
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/uniquetheo'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Twitter
            url: 'https://twitter.com/uniquetheo'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/theophilus-mensah'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: CodePen
            url: 'https://codepen.io/uniquetheo'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Discord
            url: 'https://discord.com/uniquetheo'
        styles:
          self:
            textAlign: left
      - type: FeaturedItem
        actions:
          - type: Link
            label: Instagram
            url: 'https://www.instagram.com/uniiktheo'
        styles:
          self:
            textAlign: left
    columns: 3
    spacingX: 120
    spacingY: 0
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
    subtitle: 'You can find me here:'
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: LabelsSection
    colors: colors-f
    subtitle: 'Skills:'
    items:
      - type: Label
        label: 'WEB 1, 2, 3'
      - type: Label
        label: React
      - type: Label
        label: Microsoft Office
      - type: Label
        label: Next.js
      - type: Label
        label: Netlify
      - type: Label
        label: Pancakes
      - type: Label
        label: C++
      - type: Label
        label: Swift
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: TextSection
    variant: variant-a
    subtitle: 'Contact:'
    colors: colors-f
    text: |
      [unique.theo98@gmail.com](mailto:unique.theo98@gmail.com)
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience:'
        text: |-
          **Current**

          * free agent taking orders

          **2023-2024**

          * frontend trainee at amalitech

          **2020 - **

          * Freelancer Wordpress Developer on fiverr @uniquetheo

          **2020**

          * intern developer at Bureau of Market and Social Research(MSR)

          **2017**

          * cafe attendant at Typewell Ventures
        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
      - type: FeaturedItem
        subtitle: 'Education:'
        text: |-
          **2024**

          * graduate training programme frontend development (react.js) at amalitech

          **2022-2023**

          * btech information technology (software engineering) at takoradi technical university

          **2019-2022**

          * hnd information technology at takoradi technical university

          **2017**

          * my highschool

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
    columns: 2
    spacingX: 60
    spacingY: 60
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
          - pt-8
          - pb-8
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - type: DividerSection
    styles:
      self:
        width: wide
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
        borderStyle: solid
  - type: ContactSection
    backgroundSize: full
    title: "Let’s talk... \U0001F4AC"
    colors: colors-f
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your project
          isRequired: true
          width: full
          type: TextareaFormControl
        - name: updatesConsent
          label: Sign me up to recieve my words
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-4
          - mr-4
        padding:
          - pt-12
          - pb-12
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
