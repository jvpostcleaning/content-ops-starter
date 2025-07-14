---
title: Home
slug: /
sections:
  - type: GenericSection
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        alignItems: center
        padding:
          - pt-4
          - pb-4
          - pl-4
          - pr-4
    elements:
      - type: GridBlock
        styles:
          self:
            flexDirection: row
            alignItems: center
            justifyContent: center
            gap: gap-4
        elements:
          - type: ImageBlock
            url: /images/logo.png
            altText: JV Post Cleaning Logo
            styles:
              self:
                width: w-16
                height: h-auto
                objectFit: contain
    badge:
      label:
      color: text-primary
      type: Badge

  - type: GenericSection
    title:
      text: JV Post Cleaning
      color: text-dark
      type: TitleBlock
      styles:
        self:
          textAlign: center
    text: >
      We’d like to introduce JV Post Construction Cleaning, LLC, proudly owned by Joanne
      Solis and Viridiana Moreno.
      With years of experience in the construction industry and both of us holding OSHA 10 & OSHA 30 certifications,
      we understand the high standards required for a job site to be truly complete.
      That’s why we founded JV Post Cleaning — to provide reliable, detail-oriented, and
      professional post-construction cleaning services you can count on.
    badge:
      label:
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
        padding:
          - pt-6
          - pb-6
          - pl-4
          - pr-4
          - sm:pl-8
          - sm:pr-8

  - type: FeaturedItemsSection
    title:
      text: Specializations
      color: text-dark
      styles:
        self:
          textAlign: center
          fontSize: text-sm
      type: TitleBlock
    subtitle: 
    items:
      - type: FeaturedItem
        title: Post-Construction Rough Cleaning
        subtitle:
        text:
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
          url: /images/icon1.svg
          altText: Lightning bolt symbol on red background
          styles:
            self:
              borderRadius: x-large

      - type: FeaturedItem
        title: Final Detail & Touch-Up Cleaning
        subtitle:
        text:
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
            textAlign: left
            justifyContent: center
        image:
          type: ImageBlock
          url: /images/icon2.svg
          altText: Featured icon two

      - type: FeaturedItem
        title: Industrial & Residential Clean-Up
        subtitle:
        text:
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
        im
