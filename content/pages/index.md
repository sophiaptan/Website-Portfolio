---
title: Home
layout: PageLayout
colors: colors-b
backgroundImage:
  url: null
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Sophia (P) Tan
    subtitle: Website & Graphic Designer.
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
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: center
      subtitle:
        textAlign: center
      text:
        textAlign: center
      actions:
        justifyContent: flex-start
    type: HeroSection
    text: |
      The P Stands for Patricia.
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See Portfolio
        url: /portfolio
    showDate: false
    showDescription: false
    showFeaturedImage: true
    showReadMoreLink: false
    variant: variant-b
    projects:
      - content/pages/portfolio/project-two.md
      - content/pages/portfolio/project-three.md
      - content/pages/portfolio/project-one.md
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
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
---
