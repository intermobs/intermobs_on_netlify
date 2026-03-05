---
type: PageLayout
title: About Intermobs
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
      ## Sanibonani 👋🏾

      I’m the creator behind **Intermobs** — a computer science graduate and tech-driven creative exploring how the internet moves in collective waves.

      Intermobs is a digital observatory focused on viral culture, AI-powered trends, collaborative online experiments, and the psychology of digital tribes. I analyze how internet communities form, amplify ideas, and shape modern culture in real time.

      When I’m not building with code or analyzing digital behavior, I’m experimenting with AI tools, editing visuals, and exploring emerging tech shaping the next generation of the web.
    media:
      type: ImageBlock
      url: /images/about.jpg
      altText: Intermobs creator portrait
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

  - type: TextSection
    colors: colors-f
    subtitle: "What Intermobs Is About"
    text: |
      Intermobs exists to explore how collective internet behavior shapes today’s digital world.

      From AI assistants going viral, to pixel wars, to social media flash movements — this platform studies the mechanics behind virality.

      Instead of just reporting trends, Intermobs breaks down:
      - Why something spreads
      - How algorithms amplify it
      - What digital tribes form around it
      - And what it means for the future of online culture

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

  - type: LabelsSection
    colors: colors-f
    subtitle: 'Core Skills:'
    items:
      - type: Label
        label: Web Development
      - type: Label
        label: React
      - type: Label
        label: Next.js
      - type: Label
        label: TypeScript
      - type: Label
        label: Netlify
      - type: Label
        label: Python
      - type: Label
        label: AI Tools & Automation
      - type: Label
        label: Digital Media Editing
      - type: Label
        label: Graphic Design
      - type: Label
        label: Video Editing

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

  - type: FeaturedItemsSection
    colors: colors-f
    items:
      - type: FeaturedItem
        subtitle: 'Experience'
        text: |-
          **Current**

          * Founder & Creator — Intermobs  
          * Freelance Developer & Digital Strategist  

          **Previous**

          * Full-Stack Development Projects  
          * Independent Creative & Media Work  

        styles:
          self:
            textAlign: left
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0

      - type: FeaturedItem
        subtitle: 'Education'
        text: |-
          **Bachelor’s Degree — Computer Science**

          Strong foundation in:
          * Algorithms & Data Structures  
          * Software Engineering  
          * Web Technologies  
          * Systems & Architecture  

          **Graphic Design Certification**

          Focused on digital storytelling, branding, and creative media.
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

  - type: FeaturedItemsSection
    colors: colors-f
    subtitle: 'Find Intermobs Online'
    items:
      - type: FeaturedItem
        actions:
          - type: Link
            label: GitHub
            url: 'https://github.com/intermobs/'
        styles:
          self:
            textAlign: left

      - type: FeaturedItem
        actions:
          - type: Link
            label: LinkedIn
            url: 'https://www.linkedin.com/'
        styles:
          self:
            textAlign: left

      - type: FeaturedItem
        actions:
          - type: Link
            label: Twitter / X
            url: 'https://twitter.com/'
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

      - type: FeaturedItem
        actions:
          - type: Link
            label: Discord
            url: 'https://discord.com/'
        styles:
          self:
            textAlign: left

    columns: 3
    spacingX: 120
    spacingY: 0

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
    title: "Let’s Build Something Viral 🚀"
    colors: colors-f
    text: >-
      Interested in collaboration, AI experiments, or digital culture research? Let’s connect.
    form:
      type: FormBlock
      elementId: contact-form
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
          placeholder: Email Address
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Tell me about your idea or project
          isRequired: true
          width: full
          type: TextareaFormControl
      submitLabel: "Send Message 🚀"
      styles:
        submitLabel:
          textAlign: center
---
