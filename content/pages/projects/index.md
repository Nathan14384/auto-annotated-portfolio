---
type: ProjectFeedLayout
title: Projects
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/background.avif
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 50
projectFeed:
  type: ProjectFeedSection
  colors: colors-f
  showDate: false
  showDescription: true
  showReadMoreLink: true
  showFeaturedImage: true
  variant: variant-a
  styles:
    self:
      width: narrow
      padding:
        - pt-0
        - pl-4
        - pr-4
        - pb-12
styles:
  title:
    textAlign: left
bottomSections:
  - type: FeaturedItemsSection
    title: 'Outros Trabalhos realizado em contexto de aula :'
    items:
      - type: FeaturedItem
        title: Text Based Game
        subtitle: The Killing House
        text: |


          Trabalho realizado em contexto de aula no replit usando python.
        actions:
          - type: Link
            label: Replit
            altText: ''
            url: '/https://replit.com/@Nathan-de-Sousa/The-killing-house?v=1'
            showIcon: false
            icon: arrowRight
            iconPosition: right
            elementId: ''
        elementId: ''
        styles:
          self:
            textAlign: left
    actions: []
    colors: colors-f
    columns: 1
    spacingX: 16
    spacingY: 16
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-start
---
