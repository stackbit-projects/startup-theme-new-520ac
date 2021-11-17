---
title: Blog post page
layout: PageLayout
sections:
  - type: PostFeedSection
    variant: variant-a
    colors: colors-f
    title: Blog
    showRecent: false
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
          - pt-14
          - pb-24
          - pr-4
          - pl-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-neutral
      title:
        fontWeight: '700'
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
      subtitle:
        fontWeight: '400'
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
  - elementId: ''
    colors: colors-c
    quote: |-
      “It’s great to see someone taking action while still maintaining a
      sustainable fish supply to home cooks.”
    name: Johnna Doe
    title: Product Marketing Manager at Acme
    backgroundImage:
      url: /images/post-1.jpeg
      altText: Product Marketing Manager Quote
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-36
          - pb-12
        alignItems: flex-start
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
      title:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
    type: QuoteSection
---
