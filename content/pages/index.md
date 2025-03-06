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
  - type: RecentPostsSection
    title:
      type: TitleBlock
      text: Recent posts
      color: text-dark
      styles:
        self:
          textAlign: center
    recentCount: 3
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    hoverEffect: thin-underline
    styles:
      self:
        justifyContent: center
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
