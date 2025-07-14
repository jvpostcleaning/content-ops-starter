---
title: Home
slug: /
sections:
  - type: GenericSection
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row          # Ensures image and text are side by side
        alignItems: center
        justifyContent: center
        padding:
          - pt-6
          - pb-6
          - pl-4
          - pr-4
          - sm:pl-8
          - sm:pr-8
    elements:
      - type: ImageBlock
        url: /images/main-hero.svg
        altText: Unblock your team boost your time to production preview
        elementId: ''
        styles:
          self:
            width: w-1/2
            height: h-auto
            padding: pr-4
      - type: TitleBlock
        title: JV Post Cleaning
        color: text-dark
        styles:
          self:
            textAlign: left
          text:
            fontSize: text-xs sm:text-sm
        text: >
          We’d like to introduce JV Post Construction Cleaning, LLC, proudly owned by Joanne
          Solis and Viridiana Moreno.
          With years of experience in the construction industry and both of us holding OSHA 10 & OSHA 30 certifications,
          we understand the high standards required for a job site to be truly complete.
          That’s why we founded JV Post Cleaning — to provide reliable, detail-oriented, and
          professional post-construction cleaning services you can count on.
  - type: FeaturedItemsSection
    title:
      text: Specializations
      color: text-dark
      styles:
        self:
          textAlign: center
          fontSize: text-sm
      type: TitleBlock
    items:
      - type: FeaturedItem
        title: Post-Construction Rough Cleaning
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-6
              - pl-4
              - pr-4
              - sm:pl-8
              - sm:pr-8
            borderRadius: x-large
            flexDirection: col sm:row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large

      - type: FeaturedItem
        title: Final Detail & Touch-Up Cleaning
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-6
              - pl-4
              - pr-4
              - sm:pl-8
              - sm:pr-8
            borderRadius: x-large
            flexDirection: col sm:row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Featured icon two
          url: /images/icon2.svg

      - type: FeaturedItem
        title: Industrial & Residential Clean-Up
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-6
              - pl-4
              - pr-4
              - sm:pl-8
              - sm:pr-8
            borderRadius: x-large
            flexDirection: col sm:row
        image:
          type: ImageBlock
          altText: Featured icon three
          url: /images/icon3.svg

    badge:
      label:
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-6
          - pb-6
          - pl-4
          - pr-4
          - sm:pl-8
          - sm:pr-8
        justifyContent: center
      subtitle:
        textAlign: center

seo:
  metaTitle: JV Post Cleaning
  metaDescription: JV Post Cleaning
  socialImage:
  type: Seo
type: PageLayout
---
