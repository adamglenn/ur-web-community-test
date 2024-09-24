---
title: Demo Alumni Page
type: demo_page
url: /prototypes/demo/alumni
content_blocks:
  - _bookshop_name: section/hero
    background_image:
      image: /uploads/fall-for-wvu.jpg
      alt:
    heading: Lorem Ipsum Dolor Sit Amet
    lead: Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    body:
    ctas:
      - text: Call to Action
        associate_link:
        external_link:
    config:
      is_main: false
      id: hero
      aria_labelledby: hero-1-label
    layout:
      justify_content: justify-content-start
      cols: col-xl-10
      padding: py-9
      thick_border: false
      ctas: buttons
      show_number: false
    styles:
      section: bg-wvu-blue text-white
      blend_mode: wvu-bg-blend-mode-lighten
      content_container: normal
      heading: display-2 oliviar-black text-wvu-gold
      lead: lead oliviar-thin
      body:
      buttons: btn-primary
      first_button:
      list: wvu-ul-chevrons
  - _bookshop_name: section/icon-bar
    text: Hello, world!
  - _bookshop_name: section/columns
    columns:
      - column_blocks:
          - _bookshop_name: column/hero
            background_image:
              image: /uploads/fall-for-wvu.jpg
              alt:
            heading: Lorem Ipsum Dolor Sit Amet
            lead: Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            body:
            ctas:
              - text: Call to Action
                associate_link:
                external_link:
            config:
              is_main: false
              id: hero
              aria_labelledby: hero-1-label
            layout:
              justify_content: justify-content-start
              cols: col-xl-10
              padding: py-6
              thick_border: false
              ctas: buttons
              show_number: false
            styles:
              section: bg-wvu-blue text-white
              blend_mode: wvu-bg-blend-mode-lighten
              content_container: normal
              heading: h1 oliviar-black text-wvu-gold
              lead: lead oliviar-thin
              body:
              buttons: btn-primary
              first_button:
              list: wvu-ul-chevrons
        layout:
          column_widths:
            sm: col
      - column_blocks:
          - _bookshop_name: column/hero
            background_image:
              image: /uploads/fall-for-wvu.jpg
              alt:
            heading: Lorem Ipsum Dolor Sit Amet
            lead: Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            body:
            ctas:
              - text: Call to Action
                associate_link:
                external_link:
            config:
              is_main: false
              id: hero
              aria_labelledby: hero-1-label
            layout:
              justify_content: justify-content-start
              cols: col-xl-10
              padding: py-6
              thick_border: false
              ctas: buttons
              show_number: false
            styles:
              section: bg-wvu-blue text-white
              blend_mode: wvu-bg-blend-mode-lighten
              content_container: normal
              heading: h1 oliviar-black text-wvu-gold
              lead: lead oliviar-thin
              body:
              buttons: btn-primary
              first_button:
              list: wvu-ul-chevrons
        layout:
          column_widths:
            sm: col
    layout:
      padding: py-0
      gutters:
        sm: gx-0
  - _bookshop_name: section/page-collection
    text: We’re here to help every step of the way.
    page_collection_items:
      - page: content/accessibility/_index.md
      - page: content/cms/_index.md
      - page: content/design-system/components/_index.md
  - _bookshop_name: section/quicklinks-tabbed
    text: Hello, world!
  - _bookshop_name: section/profile
    text: Hello, world!
---