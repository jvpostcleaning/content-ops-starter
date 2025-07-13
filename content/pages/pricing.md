---
title: Welcome
slug: Welcome
sections:
  - title:
      text: A team that works closely together
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Section subtitle
    text: >
We’d like to introduce JV Post Construction Cleaning, LLC, proudly owned by Joanne
Solis and Viridiana Moreno.
With years of experience in the construction industry and both of us holding OSHA 10 & OSHA 30 certifications, we understand the high standards required for a job site to be truly complete. That’s why we founded JV Post Cleaning to provide reliable, detail- oriented, and professional post-construction cleaning services you can count on.
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
    type: GenericSection
    backgroundImage:
      type: BackgroundImage
      altText: altText of the image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
      url: /images/abstract-background.svg
  - title:
      text: Flexible Pricing
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: This is the subtitle for the pricing section
    plans:
      - title: Developers
        price: Free
        details: No credit card required
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
        image:
          url: /images/abstract-feature1.svg
          altText: Pricing plan 1
          type: ImageBlock
        actions:
          - label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Professional
        price: $99
        details: per month
        description: >-
          Sed ut perspiciatis unde omnis, iste natus error sit voluptatem
          accusantium doloremque.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
        image:
          url: /images/abstract-feature2.svg
          altText: Pricing plan 2
          type: ImageBlock
        actions:
          - label: Try for free
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
      - title: Enterprise
        price: Custom
        details: per month
        description: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam.
        features:
          - Feature one
          - Feature two
          - Feature three
          - Feature four
          - Feature five
        image:
          url: /images/abstract-feature3.svg
          altText: Pricing plan 3
          type: ImageBlock
        actions:
          - label: Contact us
            url: /
            icon: arrowRight
            iconPosition: right
            style: secondary
            type: Button
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-6
              - pb-10
              - pl-6
              - pr-6
            borderRadius: large
        type: PricingPlan
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: PricingSection
seo:
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
