---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Quincy Flowers
      color: text-dark
      type: TitleBlock
    subtitle: 'Crafting Joy, One Bloom At The Time'
    text: >+
      <div style="text-align: left">Quincy Flower adalah bisnis yang bergerak di
      bidang kerajinan, khususnya di kerajinan karangan bunga. Terinspirasi oleh
      keindahan alami bunga dan kehangatan emosi yang mereka sampaikan, Quincy
      Flowers hadir untuk menciptakan karya seni yang tidak hanya estetis,
      tetapi juga penuh makna. Setiap bunga yang dibuat dengan tangan
      mencerminkan dedikasi kami untuk memberikan keindahan yang abadi kepada
      para pelanggan.</div>

    actions: []
    media:
      url: /images/main-hero.svg
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Our Products
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Most Featured Items
    items:
      - title: Bouquet
        tagline: Product
        subtitle: ''
        text: >
          Buket yang merangkai bunga artificial yang  berpenampilan dan tekstur
          yang sangat mirip dengan bunga asli.
        image:
          url: "/images/Elif\U0001F98B.jpg"
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Bloombox
        tagline: Product
        subtitle: ''
        text: >
          Rangkaian bunga artificial yang disusun dalam box atau basket yang
          elegan.
        image:
          url: /images/Flowerbox.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
      - title: Gift Box
        tagline: Product
        subtitle: ''
        text: >+
          Rangkaian bunga artificial yang yang dirancang dalam suatu frame atau
          elemen dekoratif. Cocok untuk dijadikan mahar, suvenir, dan lainnya.

        image:
          url: /images/Mahar Frame Rustic.jpg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-12
          - pl-12
          - pb-12
          - pr-12
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Our Location
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: 200%
        subtitle: Faster
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
    actions:
      - type: Button
        label: Get started
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    badge:
      type: Badge
      label: ''
      color: text-primary
      styles:
        self:
          textAlign: center
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
